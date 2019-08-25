# isomorphic-react-app
isomorphic react and notes

HOT LOADING-means that when we update react components the application will refresh, but page won't reload and the state will stay preserved. 


QUICK INFO:

The ROUTES will render in a client if the request is within the bounds of the single application or render on a server if this is a fresh request.

As soon as the server-rendered application is loaded, React boostrapd to it and the static application becomes a single page application. Once the data is fetched from a server, it is cached on a client which allows the client to display the data again without having to do another round trip.

APP displays a list of the questions from stackoverflow.If you try refreshing the page there is never the flash of the questions not being loaded. These are being loaded ona server. However once the page does loads React Boostraps toit and turning it into the single page application. By Clicking More Info button we won't be making a server request, but rather using the single page application to view details on the question. After clicking the button there was a flash of loading content as there was an asychronou server request. But if we refresh a page it is handled by a server. So pages maybe loaded one or the other way depending on how request is made. 


NODE/GIT/EXPRESS
