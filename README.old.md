Create React App

- npx create-react-app my-app
- cd my-app
npm start


REACT STATE
- Components can have state which is an object that determines how that component renders and behaves

State = {
    title: "xxx"
    body: "xxx"
    isFeatured: true
}

Create_React_App

- CLI Tool for creating React applications
- Uses webpack but needs no configuration from you
- COmes bundled with a dev server with hot reload
- "npm run build" will compile all your code to something that the browser can read


ANATOMY of A COMPONENT

Class Post extends React.Component {
    state = {
        title: 'Post One',
        body: 'This is my post'
    }

    render() {
        return (
            <div>
            <h3>{ this.state.title }</h3>
            <p>{ this.state.body }</p>
            </div>
        )
    }
}