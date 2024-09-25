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
          class="mx-auto pt-24 text-center text-7xl font-bold tracking-wide text-yellow-100 md:text-8xl lg:max-w-[60%] lg:pt-32 lg:text-9xl"
        >
          {{ message }}
        </h2>
      </header>
  
      <!-- Konten yang berada di bawah gambar background -->
      <div class="pl-20 pt-2 lg:pt-2">
        <h2 class="pt-24 text-4xl font-bold">Hi, I'm Muhammad Baihaqi</h2>
        <h3 class="text-2xl text-violet-400">Frontend Developer</h3>
        <h4 class="max-w-md text-gray-300">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Praesentium distinctio, vel iure dolores autem doloribus maiores neque laudantium nisi modi sapiente in excepturi inventore aspernatur cum ea incidunt? Ipsam vero adipisci, iure officia iusto rem!
        </h4>
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
  