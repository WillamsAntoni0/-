<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
<style>

*{
    padding:0;
    margin:0;
    box-sizing:border-box;
}


#btn{
      position: absolute;
      left: 38%;
      top:50%;
      padding: 11px;
      border-radius: 5px;
      border: none;
      width:70%;
      position: relative;
      left: 16%;
      background: green;
      cursor: pointer;
      color:white;
      padding: 10px;
      user-select:none;
}

#btn:hover{
        background: rgb(71, 231, 71);
}

h2{
    color:green;
    user-select: none;
}

input{
      outline-color:green;
      padding: 7px;
      border-radius:6px ;
      border: none;
      
}

div{
      padding: 40px;
     background-color: black;
     position: absolute;
     top:50%;
     left:50%;
    transform: translate(-50%,-50%);
    border-radius:6px ;
    }

    body{
         font-family: Arial, Helvetica, sans-serif;
         background-color: #dac9c9ce;
    }
    
  label{
        color:white;
        position:relative;
        bottom:31px;
        right:5px;
  }
  
  #checkbox{
            position:relative;
            bottom:30px;
            right:4px;
       }
       
#menu{
       background:black;
       height:50px;
       width:100%;
}

a{
   text-decoration:none;
   position:relative;
   top:23%;
   color:white;
   background:#20c023;
   padding:17.5px;
}

a:hover{
      background:green;
}

#a-1{
      color:white;
      padding:17.5px;
      position:relative;
      left:60%;
      background:none;
  }
  
#a-1:hover{
        background:#20c023;
        transition:0.3s;
}

#a-2{
      color:white;
      padding:17.5px;
      position:relative;
      background:none;
}

#a-2:hover{
         background:#20c023;
        transition:0.3s;
}

#a-3{
      color:white;
      padding:17.5px;
      position:relative;
      background:none;
}

#a-3:hover{
         background:#20c023;
         transition:0.3s;

</style>
<script src="Estudo.js"></script>
</head>
<body>
  <section id="menu">
      <a href="">Menu</a>
     <div>
      <form>
        <h2>validação.Card</h2>
       <br>
        <input placeholder="Número da agência bancária" type="number" required>
         <br><br><br>
        <input placeholder="Número da conta " type="number" required>
        <br><br><br>
<input placeholder="Telefone ou Email" required>
        <br><br><br>
        <input placeholder="Nome do Banco" type="text" required>
        <br><br><br>
     <input type="text" placeholder="Endereço ou CEP">
   <br><br><br>
   <input type="text" placeholder="Nome Completo ou CPF">
   <br><br>
   <button id="btn">Válidar dados</button>
      </form>
    </div>
  </body>
</html>
