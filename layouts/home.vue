<template>
  <div class="h-full">
    <!-- Header dengan background gambar -->
    <header
      class="coding relative min-h-[35%] bg-cover bg-top md:min-h-[44%] lg:bg-center"
    >
      <div class="pt-0 md:pt-2"></div>
      <TopNav />

      <!-- Jika `message` ada, tampilkan message -->
      <h2
        v-if="message"
        class="mx-auto pt-24 text-center text-5xl font-bold tracking-wide text-yellow-100 md:text-6xl lg:max-w-[60%] lg:pt-32 lg:text-8xl"
      >
        {{ message }}
      </h2>
    </header>

    <!-- Konten yang berada di bawah gambar background -->
    <div class="flex flex-col lg:flex-row justify-between items-center px-6 lg:px-20 pt-8">
      <!-- Bagian teks -->
      <div class="text-center lg:text-left">
        <h2 class="text-3xl lg:text-4xl font-bold">Hi, I'm Muhammad Baihaqi</h2>
        <h3 class="text-xl lg:text-2xl text-violet-400">Frontend Developer</h3>
        <h4 class="max-w-md text-gray-300 mt-4">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Praesentium distinctio, vel iure dolores autem doloribus maiores neque laudantium nisi modi sapiente in excepturi inventore aspernatur cum ea incidunt? Ipsam vero adipisci, iure officia iusto rem!
        </h4>
      </div>

      <!-- Gambar profil di sebelah kanan pada layar besar, di atas/bawah teks pada layar kecil -->
      <div class="mt-6 lg:mt-0 lg:ml-8">
        <img
          src="@/assets/img/haqi.jpg"
          alt="Profile"
          class="w-32 h-32 rounded-full object-cover border-4 border-violet-400 mx-auto lg:mx-0"
        />
      </div>
    </div>

    <main>
      <slot />
    </main>

    <MFooter />
  </div>
</template>

<script setup lang="ts">
const layoutCustomProps = useAttrs();
const message = layoutCustomProps.message;
console.log(message);
</script>

<style scoped>
.coding {
  background-image: linear-gradient(
      rgba(0, 0, 0, 0) 10%,
      rgb(3, 7, 18)
    ),
    url("@/assets/img/coding.jpg");
  background-size: cover;
  background-position: center;
}
</style>
