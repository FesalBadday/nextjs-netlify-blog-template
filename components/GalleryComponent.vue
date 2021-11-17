<template>
  <section class="grid justify-items-center p-14 text-5xl bg-gray-400">
    <h2>Gallery</h2>
    <p class="p-14">
      Lorem ipsum dolor sit amet consectetur, adipisicing elit. Laboriosam
      exercitationem hic cupiditate nesciunt corporis, quia qui. Aut dolorum
      consequatur eum aliquam rerum et necessitatibus, odit ullam reprehenderit
      doloremque, neque sequi?
    </p>

    <div class="flex justify-evenly gap-x-16 gap-y-16 flex-wrap p-14">
      <nuxt-img
        src="assets/images/gal-car-1.jpg"
        sizes="sm:300px md:400px lg:500px"
      />
      <nuxt-img
        src="assets/images/gal-car-2.jpg"
        sizes="sm:300px md:400px lg:500px"
      />
      <nuxt-img
        src="assets/images/gal-car-3.jpg"
        sizes="sm:300px md:400px lg:500px"
      />
    </div>
  </section>
</template>
