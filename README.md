# Dhyanio-Video-Chat-App

## Technologies
- golang
- React

### Backend

Written in Go. A simple WebSocket server for signalling implemented using 
[gorilla/websocket](https://github.com/gorilla/websocket)

* `go build` to compile and build the binary
* `./dhyanio-video-chat` to run the backend server on `:8000`

### Frontend

The `client` is written in React and uses [Vite](https://vitejs.dev/) for the dev server. Run the following commands in the `client` directory

* `npm i` to install all the dependencies
* `npm run dev` to start the local dev server
