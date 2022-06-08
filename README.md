# 404-NotFound-page-in-React--using-HTML-CSS
All you need is to import the 404file (Error.jsx) into your app.js and call it .....
i.e

App.js
import Error from "./Pages/Error/Error";

function App() {

  return (
  
    <div className="App">
	<Error/>
    </div>
    
         );
  
}

export default App;



// /* allows you that if u enter anything addionally like localhost:3000/aakjdsa
   it will take you to the 404 page
   
// If you want to do routing

        <Route path="/*" element={<Error />} />

![errornotfound](https://user-images.githubusercontent.com/100490953/172716150-ea55e461-b97a-4764-86ff-25222cf1f77c.png)
