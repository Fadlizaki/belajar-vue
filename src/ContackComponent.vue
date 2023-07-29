<template>
   <div class="container mx-auto px-4">
  <body class="ml-20">
    <center>
    <b class="p-2"
          style="font-size: 30px; text-align: center; color: black; font-family: 'sans-serif', Calibri, 'Trebuchet MS', sans-serif;">Kontak</b>
          <div style="width: 10%; background: rgb(10, 47, 229); height: 5px;"></div>
          <br>
    <form>
      <div>
        <label for="name">Whatsap</label>
        <button class="bg-green-600" type="submit" >
          <a href="https://wa.me/6283137969755?text=halo%20fadli%20">CLICK DISINI</a>
        </button>
      </div>
      <div>
        <label for="name">Email</label>
        <button class="bg-blue-600" type="submit" >
          <a href="mailto:fdlizaki26@gmail.com?subject=Ini%20adalah%20judul%20email%20default&body=Pesan%20ini%20akan%20secara%20otomatis%20muncul%20lho%21">CLICK DISINI</a>  
        </button>
      </div>
      <div>
        <label for="name">Git Hub</label>
        <button class="bg-red-600" type="submit" >
          <a href="https://github.com/Fadlizaki">CLICK DISINI</a>
        </button>
      </div>
    </form>
    </center>
  </body>
  </div>
</template>

<style scoped>
  h1 {
    font-size: 1.8rem;
    font-weight: bold;
    margin-bottom: 1rem;
  }
  .form-fields {
    margin-bottom: 1rem;
  }
  label { 
    display: block; 
    margin-bottom: 4px; 
    font-weight: bold; 
    font-size: 0.9rem;
  }
  input[type="text"], input[type="email"], textarea {
    border: 1px solid #ccc;
    font-size: 1rem;
    padding: 6px 10px;
    border-radius: 4px;
  }
  body { display: block }
  button[type="submit"] { 
    color: white;
    font-size: 0.8rem;
    border: none;
    border-radius: 4px;
    padding: 8px 12px;
    font-weight: 500;
  }
</style>