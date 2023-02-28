<template>
  <div id="Main-Div">
    <div id="MainPage">
      <Header/>
      <img id="MPlogo" src="../public/MPlogo.svg"/>
      <h1 id="Name">Daniel Komonii</h1>
    </div>
    <div id="About">
        <p id="About-Text">My name is Daniel, I was born in Ukraine in 2004.<br> 
        Since 2015 I am living in Germany<br>
        I am interested in web development.<br>
        Currently I am actively learning how front- and backend work.<br>
        I would like to start an IT company in the future.
        </p>
    </div>
    <div  id="Service">
      <p id="Service-Text">If you are interested in a cheap and modern website<br>
        for your business or for yourself,<br>
        you can contact me using the contact form below,<br>
        and I will get in touch with you as soon as possible
      </p>

      <div id="Pricing-Main">
        <div id="Pricing-Header">
          <p id="Pricing-Header-Text">Price</p>
        </div>

        <p id="Pricing-Main-Text">Start at 50€<br>
        +</p>
        <p id="Pricing-Main-Text2">Around 10€/mo<br>
        for hosting and support</p>
      </div>
    </div>
    <div id="Contact">

      <div id="Placeholder-div">
        <p id="Placeholder">Write Your name here</p>
        <p id="Placeholder">Email here</p>
        <p id="Placeholder">Request here</p>
      </div>
      <form id="Contact-Body" onsubmit="">
          <input id="Name-input" placeholder="Name" required/>
          <input id="Email-input" placeholder="Email" required/>
          <textarea  rows="10" cols="50" placeholder="Request" id="Request-input" required></textarea>
          <button type="submit" onclick="" id="Btn-submit">Send</button>
      </form>
    </div>
  </div>
</template>

<script>
  import "@/assets/styles.css"
  import Header from "./components/Header.vue"
export default {
  
  name: 'App',
  components: {
    Header
  }
}
</script>
