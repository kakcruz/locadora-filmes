<!-- NavBar do projeto está toda neste arquivo App.vue -->
<template>
  <header class="bg-black">
    <div class="container mx-auto wrapper">
      <nav class="flex items-center justify-center">
        <a href=""><img src="./assets/img/filme.png" alt="" /></a>
        <div class="flex items-center">
          <a href="" class="bg-black hover:bg-blue-400 active:bg-indigo-500"
            >Home</a
          >
          <a href="" class="bg-black hover:bg-blue-400 active:bg-indigo-500"
            >Filmes</a
          >
          <a href="" class="bg-black hover:bg-blue-400 active:bg-indigo-500"
            >Sua conta</a
          >
          <div class="buscar"></div>
          <div class="grid mt-4 mr-5 ml-10">
            <select
              class="appearance-none row-start-1 col-start-1 bg-blue-400 hover:bg-blue-400 p-1 rounded-xl cursor-pointer"
            >
              <option>Olá, Karoline</option>
              <option>
                <a
                  href="/home/kakcruz/locadora-challenge/src/views/LoginPage.vue"
                  >Sair</a
                >
              </option>
            </select>
          </div>
          <img
            src="./assets/img/perfil.png"
            alt="profile"
            class="img-profile"
          />
        </div>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: "App",
  components: {},
};
</script>

<style scoped>
header {
  line-height: 1.5;
  max-height: 100vh;
}

nav {
  width: 100%;
  height: 125px;
  font-size: 18px;
  color: white;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
  margin-top: 10px;
}

nav a:hover {
  border-radius: 10px;
}

img {
  width: 100px;
  height: 100px;
}

.img-profile {
  width: 50px;
  height: 50px;
  margin-left: -14px;
  margin-top: 8px;
}

.icon-search {
  width: 20px;
  height: 20px;
}

select {
  font-size: 15px;
}

input {
  color: black;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  nav {
    text-align: left;
    margin-left: -1rem;
    font-size: 1rem;

    padding: 1rem 0;
    margin-top: 1rem;
  }
}
</style>
