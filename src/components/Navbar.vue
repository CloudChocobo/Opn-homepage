<template>
	<div class="navbar">
		<a href="#" class="nav" v-on:click="makeActive('Home')"
			><img alt="home icon" src="../assets/navbar/Home.svg"
		/></a>
		<ButtonNavBar route="/barconnecté" label="Le bar connecté"
			>Le bar connecté</ButtonNavBar
		>
		<ButtonNavBar route="/cartouches" label="Cartouches"
			>Cartouches</ButtonNavBar
		>
		<ButtonNavBar route="/accessoires" label="Accessoires"
			>Accessoires</ButtonNavBar
		>
		<img alt="O" src="../assets/navbar/O.svg" />
		<img alt="P" src="../assets/navbar/P.svg" />
		<img alt="N" src="../assets/navbar/N.svg" />
		<img alt="paille" src="../assets/navbar/paille.svg" />
		<ButtonNavBar route="/cocktails" label="Cocktails"
			>Cocktails</ButtonNavBar
		>
		<ButtonNavBar route="/food" label="Food">Food</ButtonNavBar>
		<ButtonNavBar route="/recevoir" label="Recevoir">Recevoir</ButtonNavBar>
		<a href="#" class="nav" v-on:click="makeActive('search')"
			><img alt="subtract icon" src="../assets/navbar/Subtract.svg"
		/></a>
		<a href="#" class="nav" v-on:click="makeActive('user')"
			><img alt="user icon" src="../assets/navbar/User.svg"
		/></a>
		<a href="#" class="nav" v-on:click="makeActive('union')"
			><img alt="union icon" src="../assets/navbar/Union.svg"
		/></a>
		<a href="#" class="nav" v-on:click="makeActive('(nb)')"
			><img alt="nb icon" src="../assets/navbar/(nb).png"
		/></a>
	</div>
</template>

<script>
import ButtonNavBar from "@/components/ButtonNavBar.vue";
export default {
	name: "Navbar",
	components: { ButtonNavBar },
};
</script>

<style scoped>
.nav {
	display: flex;
	flex-direction: row;
	width: 78px;
	height: 20px;

}

.navbar {
	display: flex;
	flex-direction: row;
	align-items: center;
	justify-content: center;
	text-align: center;
	height: 80px;
	width: 100%;
	background: transparent;
}
</style>
