<script>
export default {};
</script>

<template>
  <footer class="footer bg-[#26435E] pt-20 pb-10">
    <div class="container mx-auto px-10 sm:px-12">
      <div class="footer-container space-y-10">
        <div class="logo flex justify-between items-center">
          <p class="font-jolly text-2xl text-white">Moneydash</p>

          <ul class="flex space-x-3">
            <li>
              <a href="#">
                <img class="w-7" src="../assets/icons/twitter.svg" alt="" />
              </a>
            </li>
            <li>
              <a href="#">
                <img class="w-7" src="../assets/icons/youtube.svg" alt="" />
              </a>
            </li>
            <li>
              <a href="#">
                <img class="w-7" src="../assets/icons/youtube.svg" alt="" />
              </a>
            </li>
            <li>
              <a href="#">
                <img class="w-7" src="../assets/icons/dribble.svg" alt="" />
              </a>
            </li>
          </ul>
        </div>

        <div
          class="
            footer-links
            relative
            before:absolute
            after:absolute
            before:bg-white
            after:bg-white
            before:h-px
            after:h-px
            before:w-full
            after:w-full
            before:-top-2
            after:-bottom-2
            before:left-0
          "
        >
          <ul
            class="
              font-montserrat
              text-white text-sm
              w-full
              flex
              justify-around
            "
          >
            <li><a href="#">Products</a></li>
            <li><a href="#">About us</a></li>
            <li><a href="#">Contact!</a></li>
          </ul>
        </div>

        <div
          class="
            credits
            font-montserrat
            text-[10px] text-center text-white
            space-y-1
          "
        >
          <p class="developer">
            Designed by
            <span class=""
              ><a class="text-[#3F6F9C]" href="#">BOLANLE OLANIYAN</a></span
            >
          </p>

          <p class="developer">
            Developed by
            <span class=""
              ><a class="text-[#3F6F9C]" href="#">GANIYU IDRIS</a></span
            >
          </p>
        </div>
      </div>
    </div>
  </footer>
</template>

<style scoped></style>
