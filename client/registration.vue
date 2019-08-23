<style>
	#web{
	background-color: red;
	color: white;
	border: 2px solid red;
	width: 500px;
	}

	input, #web{
		box-shadow: 0 0 7px rgba(0,0,0,0.5);
	}
</style>


<template>
	<div>
		<form>
			  <div class="form-group">
			    <input type="login" class="form-control" id="login" aria-describedby="emailHelp" placeholder="Логин">
			  </div>
			  <div class="form-group">
			    <input type="password" class="form-control" id="password" placeholder="Пароль">
			  </div>
			  <div class="form-group">
			    <input type="password" class="form-control" id="repeat password" placeholder="Повтор пароля">
			  </div>
			  <button type="submit" class="btn btn-primary" id="web">Зарегистрироваться!</button>
		</form>
	</div>
</template>