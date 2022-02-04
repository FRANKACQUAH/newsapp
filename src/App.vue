<template>
  <div>
    <Header />
    <Carosel />
    <div class="lowerbanner">
    <div class="page1 col-6">
      <h1>CONTENT OVERVIEW</h1>
      <img id="logo" src="@/assets/img1.jpg" />
      <p>
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Odio tenetur
        autem, aut, laboriosam a dolore quas ullam cumque magnam praesentium,
        explicabo quis incidunt enim numquam ut? Dolorem quibusdam cumque
        dignissimos! Lorem ipsum dolor sit amet consectetur, adipisicing elit.
        Odio tenetur autem, aut, laboriosam a dolore quas ullam cumque magnam
        praesentium, explicabo quis incidunt enim numquam ut? Dolorem quibusdam
        cumque dignissimos! Lorem ipsum dolor sit amet
        <a href="google.com" style="color: orange"> Read More </a>
      </p>
    </div>
    <div class="page2 col-6">
      <h1>CONTENT OVERVIEW</h1>
      <p>
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Odio tenetur
        autem, aut, laboriosam a dolore quas ullam cumque magnam praesentium,
        explicabo quis incidunt enim numquam ut? Dolorem quibusdam cumque
        dignissimos! Lorem ipsum dolor sit amet consectetur, adipisicing elit.
        Odio tenetur autem, aut, laboriosam a dolore quas ullam cumque magnam
        praesentium, explicabo quis incidunt enim numquam ut? Dolorem quibusdam
        cumque dignissimos! Lorem ipsum dolor<a
          href="google.com"
          style="color: orange"
        >
          Read More</a
        >
        <img id="logo" src="@/assets/ndc.jpg" />
      </p>
    </div>
    </div>
    <div class="smallcentent">
    <div class="card col-4">
  <img src="@/assets/ndc.jpg" alt="Avatar" style="width:100%">
  <div class="container">
    <h4><b>John Doe</b></h4>
    <p>Architect & Engineer</p>
  </div>
</div>
<div class="card col-4">
  <img src="@/assets/ndc.jpg" alt="Avatar" style="width:100%">
  <div class="container">
    <h4><b>John Doe</b></h4>
    <p>Architect & Engineer</p>
  </div>
</div>
<div class="form">
<div class="card col-3">
  <img src="@/assets/ndc.jpg" alt="Avatar" style="width:100%">
  <div class="container">
    <h4><b>John Doe</b></h4>
    <p>Architect & Engineer</p>
    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. gshshh gsggsgsgs gsgs</p>
  </div>
</div>
</div>
<form action="action_page.php">
  <div class="container">
    <hr>
    <h2>Register as a News Editor</h2>
    <p>Please fill in this form to create an account.</p>
    <label for="email"><b>Email</b></label>
    <input type="text" placeholder="Enter Email" name="email" id="email" required>

    <label for="psw"><b>Password</b></label>
    <input type="password" placeholder="Enter Password" name="psw" id="psw" required>

    <label for="psw-repeat"><b>Repeat Password</b></label>
    <input type="password" placeholder="Repeat Password" name="psw-repeat" id="psw-repeat" required>
    <hr>

    <p>By creating an account you agree to our <a href="#">Terms & Privacy</a>.</p>
    <button type="submit" class="registerbtn">Register</button>
  </div>

  <div class="container signin">
    <p>Already have an account? <a href="#">Sign in</a>.</p>
  </div>
</form>
</div>
<footer class="page-footer">
          <div class="container">
            <div class="row">
              <div class="col l6 s12">
                <h5 class="white-text">My Ghana News App</h5>
                <p class="grey-text text-lighten-4">YYour best news source with authentic references YYour best news source with authentic references</p>
              </div>
              <div class="col l4 offset-l2 s12">
                <h5 class="white-text">Links</h5>
                <ul>
                  <li><a class="grey-text text-lighten-3" href="#!">About Us</a></li>
                  <li><a class="grey-text text-lighten-3" href="#!">International News</a></li>
                  <li><a class="grey-text text-lighten-3" href="#!">Trending</a></li>
                  <li><a class="grey-text text-lighten-3" href="#!">Local News</a></li>
                </ul>
              </div>
            </div>
          </div>
          <div class="footer-copyright">
            <div class="container">
            © 2022 Copyright
            <a class="grey-text text-lighten-4 right" href="#!">More Links</a>
            </div>
          </div>
        </footer>
            
  </div>
</template>
<script>
import Carosel from "./components/carosel.vue";
import Header from "./components/header.vue";

export default {
  name: "App",
  components: {
    Carosel,
    Header,
  },
};
</script>

<style scoped>
h1 {
  font-size: 20px;
  font-family: "Lucida Sans", "Lucida Sans Regular", "Lucida Grande",
    "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
  text-align:center;
}
.page1 {
  margin: 24px;
  float: left;
  width: 625px;
  height: 580px;
  padding:15px;
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
}
.page2 {
  margin: 24px;
  float: left;
  width: 625px;
  height: 580px;
  padding:1px;
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
}
#logo {
  width: 600px;
  height: 300px;
}

.card {
  /* Add shadows to create the "card" effect */
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  transition: 0.3s;
  margin:5px;
  padding:5px;
  float:left;
  text-align:center;
}

/* On mouse-over, add a deeper shadow */


/* Add some padding inside the card container */
.container {
  padding: 2px 16px;
}
* {box-sizing: border-box}

/* Add padding to containers */
/* Full-width input fields: form details*/
input[type=text], input[type=password] {
  width: 100%;
  padding: 15px;
  margin: 5px 0 22px 0;
  display: inline-block;
  border: none;
  background:white;
}

input[type=text], input[type=password] {
  background-color: #ddd;
  outline: none;
}

/* Overwrite default styles of hr */
hr {
  border: 1px solid #f1f1f1;
  margin-bottom: 25px;
}

/* Set a style for the submit/register button */
.registerbtn {
  background-color: #04AA6D;
  color: white;
  padding: 16px 20px;
  margin: 8px 0;
  border: none;
  cursor: pointer;
  width: 100%;
  opacity: 0.9;
}

.registerbtn:hover {
  opacity:1;
}

/* Add a blue text color to links */
a {
  color: dodgerblue;
}

/* Set a grey background color and center the text of the "sign in" section */
.signin {
  background-color: #f1f1f1;
  text-align: center;
}
.page-footer{
    display: flex;
    min-height: 100px;
    flex-direction: column;
    background-color:black;
    color:white;
  }  main {
    flex: 1 0 auto;
  }
  li{
    list-style:none;
  }
</style>
