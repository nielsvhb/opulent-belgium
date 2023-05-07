<template>
  <div>
  <header>
    <Nav />
  </header>
  <main>
    <ProjectSlider />
    <section class="py-32 bg-fuchsia bg-cover" id="about" style="background-image: url('/grote parel.png')" >
      <div class="mx-auto sm:container">
        <h1 class="text-primary font-heading text-5xl inline-block mb-10">
          Interior design <span class="font-body text-xl block text-right mt-2 font-regular">for the daring</span>
        </h1>
        <p class="w-1/2 text-primary leading-7">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Earum ipsam quas,
          aspernatur nulla quae blanditiis amet, sed suscipit ratione voluptatibus
          perspiciatis pariatur. Minus ab nostrum officiis consectetur nisi officia
          explicabo. Lorem ipsum dolor sit amet consectetur adipisicing elit. Earum
          ipsam quas, aspernatur nulla quae blanditiis amet, sed suscipit ratione
          voluptatibus perspiciatis pariatur. Minus ab nostrum officiis consectetur
          nisi officia explicabo.
        </p>
      </div>
    </section>

    <section style="background-image: url(/spacejoy.jpg);" class="py-32 bg-cover bg-center min-h-[60vh]">
      <div class="ml-[60%] inline-flex justify-center items-center w-1/4 relative">

        <p class="text-white z-10 absolute p-16 px-24">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cumque dolorem dolores enim ex exercitationem hic
          iusto magnam nam, officia sed! Aliquam at debitis deserunt ducimus nesciunt possimus.
        </p>
        <img src="/blob.png" alt="blob" class="relative inset-0 z-0"/>
      </div>
    </section>


    <section class="py-32 bg-fuchsia-dark text-white" id="process">
      <div class="mx-auto sm:container">
        <div class="flex">
          <div class="w-1/4">
            <h2 class="text-primary font-heading text-3xl inline-block mb-10 text-white">
              FAQ
            </h2>
          </div>
          <div class="w-3/4 ">
            <ul>
              <li class="mb-10">
                <div class="mb-3 font-semibold">Lorem ipsum dolor sit amet?</div>
                <div>
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit. Animi fugiat, minus? Alias, blanditiis cumque dicta fuga officia provident qui quibusdam temporibus! Amet asperiores ea excepturi ipsum quibusdam rem sed ut!
                </div>
              </li>
              <li class="mb-10">
                <div class="mb-3 font-semibold">Lorem ipsum dolor sit amet?</div>
                <div>
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit. Animi fugiat, minus? Alias, blanditiis cumque dicta fuga officia provident qui quibusdam temporibus! Amet asperiores ea excepturi ipsum quibusdam rem sed ut!
                </div>
              </li>
              <li>
                <div class="mb-3 font-semibold">Lorem ipsum dolor sit amet?</div>
                <div>
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit. Animi fugiat, minus? Alias, blanditiis cumque dicta fuga officia provident qui quibusdam temporibus! Amet asperiores ea excepturi ipsum quibusdam rem sed ut!
                </div>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </section>


    <section class="py-32 bg-primary" id="contact">
      <div class="mx-auto sm:container">
        <div class="text-center">
          <h2 class="text-white font-heading text-3xl inline-block mb-10">
            Contact
          </h2>
        </div>
        <div class="flex">
          <div class="w-1/2 pr-32">
            <p class="text-white mb-8 mt-8">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. A accusamus architecto asperiores aspernatur corporis delectus earum esse eum.  A accusamus architecto asperiores aspernatur corporis delectus earum esse eum.
            </p>
            <ul class="flex space-x-6 ml-12">
              <li>
                <a href="">
                  <img src="/instagram.png" alt="instagram" width="45" />
                </a>
              </li>
              <li>
                <a href="">
                  <img src="/telefoon.png" alt="phone" width="45" />
                </a>
              </li>
              <li>
                <a href="">
                  <img src="/email.png" alt="e-mail" width="45" />
                </a>
              </li>
            </ul>
          </div>
          <div class="w-1/2">
            <form class="pl-24">
              <div class="flex space-x-6">
                <div class="w-1/2">
                  <label for="firstname" class="block text-white mb-1">Name</label>
                  <input id="firstname" name="firstname" type="text" class="bg-primary-light px-4 py-2 rounded w-full">
                </div>
                <div class="w-1/2">
                  <label for="surname" class="block text-white mb-1">Surname</label>
                  <input id="surname" name="surname" type="text" class="bg-primary-light px-4 py-2 rounded w-full">
                </div>
              </div>
              <div class="mt-6">
                <div class="w-full">
                  <label for="email" class="block text-white mb-1">Email</label>
                  <input id="email" name="email" type="text" class="bg-primary-light px-4 py-2 rounded w-full">
                </div>
              </div>
              <div class="mt-6">
                <div class="w-full">
                  <label for="message" class="block text-white mb-1">Your message</label>
                  <textarea id="message" name="message" class="bg-primary-light px-4 py-2 rounded w-full" rows="4"></textarea>
                </div>
              </div>
              <div class="mt-6">
                <button class="font-semibold text-white bg-primary-light hover:bg-fuchsia hover:text-black rounded px-6 py-2 w-48">Send</button>
              </div>
            </form>
          </div>
        </div>

        <div class="flex mt-20">
          <div class="ml-auto text-white text-right flex">
            Opulent Co. 2023 All rights reserved. <img class="ml-4 w-8"  src="pearl.png" alt="logo pearl" />
          </div>
        </div>
      </div>
    </section>

  </main>
  <footer>

  </footer>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import Nav from "../components/nav.vue";
import ProjectSlider from "../components/project-slider.vue";

export default Vue.extend({
  name: 'IndexPage',
  components: {
    Nav,
    ProjectSlider
  }
})
</script>
