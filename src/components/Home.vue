<template>
  <div class="home flex justify-center flex-col items-center">
      <img class="h-64 w-full object-cover" src="https://source.unsplash.com/random" alt />
    <div class="flex flex-col items-center bg-gray-400 w-1/4 p-10 rounded-lg shadow-xl">
      <img class="h-64 w-64 rounded-full" src="https://source.unsplash.com/random" alt />
      <h5 class="text-2xl font-semibold">Image info</h5>
      <p class="text-left mt-4">
        Lorem ipsum, dolor sit amet consectetur adipisicing elit.
        Laboriosam fugiat doloremque id veritatis obcaecati incidunt reiciendis quo laborum qui quaerat fugit accusantium,
        animi rerum esse a quidem voluptas ullam dolor!
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home"
};
</script>

<style>
</style>