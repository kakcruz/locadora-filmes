<template>
  <body>
    <div
      class="flex items-center justify-center min-h-screen container mx-auto"
    >
      <!-- Grid -->
      <div class="grid grid-cols-1 md:grid-cols- lg:grid-cols-3 gap-8">
        <!-- Card -->
        <div class="rounded-xl shadow-lg">
          <div class="p5- flex flex-col">
            <div class="rounded-xl overflow-hidden">
              <img
                src="../assets/img/filme-ultimato.jpeg"
                alt="Capa do filme Vingadores"
              />
            </div>
            <h5
              class="text-blue-500 text-2xl md1:text-3xl font-medium mt-5 px-5"
            >
              The avengers
            </h5>
            <p
              class="text-gray-300 text-sm mt3 font-medium mt-2 px- text-justify"
            >
              Após Thanos eliminar metade das criaturas vivas, os Vingadores têm
              de lidar com a perda de amigos e entes queridos. Com Tony Stark
              vagando perdido no espaço sem água e comida, Steve Rogers e
              Natasha Romanov lideram a resistência contra o titã louco.
            </p>
            <a
              href=""
              class="text-center bg-blue-400 text-black py-2 rounded-lg font-semibold mt-4 hover:bg-indigo-500 focus:scale-95 transition-all duration-200 ease-out"
              >Reproduzir</a
            >
          </div>
        </div>
        <div class="rounded-xl shadow-lg">
          <div class="p5- flex flex-col">
            <div class="rounded-xl overflow-hidden">
              <img
                src="../assets/img/super-mario.jpg"
                alt="Capa Super Mario Bros"
              />
            </div>
            <h5
              class="text-blue-500 text-2xl md1:text-3xl font-medium mt-5 px-5"
            >
              Super Marios Bros
            </h5>
            <p
              class="text-gray-300 text-sm mt3 font-medium mt-2 px- text-justify"
            >
              Mario e seu irmão Luigi são encanadores. Um dia, eles vão parar no
              reino dos cogumelos, governado pela Princesa Peach. O local é
              ameaçado por Bowser, rei dos Koopas, que faz de tudo para
              conseguir reinar em todos os lugares.
            </p>
            <a
              href=""
              class="text-center bg-blue-400 text-black py-2 rounded-lg font-semibold mt-4 hover:bg-indigo-500 focus:scale-95 transition-all duration-200 ease-out"
              >Reproduzir</a
            >
          </div>
        </div>
        <div class="rounded-xl shadow-lg">
          <div class="p5- flex flex-col">
            <div class="rounded-xl overflow-hidden">
              <img
                src="../assets/img/filme-velozes-furiosos.jpg"
                alt="Capa do filme Vingadores"
                width="400px"
              />
            </div>
            <h5
              class="text-blue-500 text-2xl md1:text-3xl font-medium mt-5 px-5"
            >
              Velozes e Furiosos 9
            </h5>
            <p
              class="text-gray-300 text-sm mt3 font-medium mt-2 px- text-justify"
            >
              Brian O'Conner é um policial que se infiltra no submundo dos
              rachas de rua para investigar uma série de furtos. Enquanto tenta
              ganhar o respeito e a confiança do líder Dom Toretto, ele corre o
              risco de ser desmascarado.
            </p>
            <a
              href=""
              class="text-center bg-blue-400 text-black py-2 rounded-lg font-semibold mt-4 hover:bg-indigo-500 focus:scale-95 transition-all duration-200 ease-out"
              >Reproduzir</a
            >
          </div>
        </div>
      </div>
    </div>
  </body>
</template>

<style scoped>
body {
  background-color: black;
}
</style>

<script>
export default {
  name: "HomeView",
};
</script>
