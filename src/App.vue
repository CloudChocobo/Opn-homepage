<template>
	<Header>
		<img class="cover" alt="cover photo" src="./assets/IMG.png" />
		<Navbar></Navbar>
		<div class="container">
			<div class="H1">
				<H1>L'expérience cocktail à la maison</H1>
			</div>
			<div class="H3">
				<H3>Opn, votre bar connecté à domicile</H3>
				<p>
					Le premier bar connecté qui vous permet de créer des
					centaines de cocktais à la maison en s'amusant.
				</p>
				<div class="link">
					<a href=""
						><img alt="polygon" src="./assets/Polygon.png" />
						DÉCOUVRIR OPN EN DÉTAILS - 1'40</a
					>
				</div>
				<Button>Découvrir le starter pack</Button>
				<div class="link">
					<a href="">DÉJA OPNER? RECHARGEZ VOTRE BAR.</a>
				</div>
			</div>
		</div>
	</Header>
	<Main>
		<div class="H2">
			<H2> Redécouvrez le plaisir d'une soirée cocktails à la maison</H2>
		</div>
		<section>
			<div class="player">
				<img alt="player photo" src="./assets/image.png" />
			</div>
		</section>
	</Main>
	<Footer>
		<div class="link">
			<a href="">CGU</a>
		</div>
		<div class="link">
			<a href="#">MENTIONS LÉGALES</a>
		</div>
		<div class="link">
			<a href="#">COOKIES</a>
		</div>
	</Footer>
</template>

<script>
import Navbar from "@/components/Navbar.vue";
import Button from "@/components/Button.vue";
export default {
	name: "App",
	components: {
		Navbar,
		Button,
	},
};
</script>

<style>
/*style général de la page*/
* {
	font-family: Canela, Arial, Helvetica, sans-serif;
	padding: 0px;
	margin: 0px;
	text-align: justify;
	box-sizing: border-box;
}

Header,
Footer {
	width: 100%;
}
body {
	background: #f5f6f6;
}

Header {
	height: 620px;
}
Header h1 {
	color: #fff;
	font-size: 3.1em;
	line-height: 1em;
	width: 34%;
	margin: 0 auto;
	text-align: left;
}
Header h3 {
	color: #fff;
	font-size: 1.2em;
	line-height: 1em;
	width: 75%;
	text-align: left;
  margin-top: 10%;
}
Header p {
  color: #fff;
	font-size: 1em;
	line-height: 1em;
	width: 44%;
	text-align: left;
}
Header .link{
    color: #fff;
	font-size: 0.8em;
	line-height: 1em;
	width: 75%;
	text-align: left;
}
Header .button .img{
	background-color: white;
	font-size: 1em;
	line-height: 1em;
	width: 75%;
	text-align: left;
}
H2 {
	color: #000;
	font-size: 32px;
	line-height: 38.4px;
	width: 100%;
}
Footer {
	display: flex;
	flex-direction: row;
	background-color: #6c6d72;
	border-top: 2px solid #6c6d72;
	width: 100%;
	height: 60px;
	justify-content: center;
}
Footer .link {
	width: 90%;
	margin: 0 auto;
	color: #fff;
	text-align: center;
}

.cover {
	display: flex;
	flex-direction: column;
	width: 100%;
	z-index: 0;
}
.navbar {
	display: flex;
	flex-direction: row;
	justify-content: center;
	text-align: center;
	width: 100%;
	z-index: 2;
	position: relative;
	margin-top: -43%;
}
.container {
	display: flex;
	flex-direction: row;
  width: 98%;
  height: 75%;
  margin-top: 2%;
  align-items: center;
  justify-content: space-between;
}
.container .H1 {
	display: flex;
	flex-direction: column;
	align-items: center;
	width: 50%;
	height: 50%;
}
.container .H3 {
    display: flex;
    flex-direction: column;
    align-items: left;
    margin-top: 3%;
    width: 40%;
    height: 50%;
}

.Button{
    display: flex;
    flex-direction: column;
    margin-right: 30%;
    width: 47%;
    height: 47%;
}
.H2 {
	margin-top: 13%;
	margin-left: 15%;
	padding: 0% 10% 0% 10%;
	background-color: #fff;
	height: 86px;
	width: 50%;
	display: flex;
	flex-direction: column;
	justify-content: flex-end;
	align-content: center;
}
.player {
	display: flex;
	flex-direction: column;
	width: 25%;
	margin-top: 10%;
}


</style>
