<script>
    import profileImage from '../assets/makoto.jpeg';
</script>
  
  <!-- Nav.svelteの`href="#about"`と紐づく`id`を指定する -->
<section id="about">
    <div class="py-32 text-gray-600">
      <h1 class="text-center mb-10 font-medium text-3xl">ABOUT ME</h1>
      <div class="flex flex-wrap lg:w-4/5 sm:mx-auto">
        <div class="p-2 md:w-1/2 w-full">
          <img src={profileImage} alt="" class="mx-auto mt-24 md:mt-0" />
        </div>
        <div class="flex flex-col text-center p-2 md:w-1/2 w-full">
          <h1 class="text-gray-900 mb-10 font-medium">喉越生太郎</h1>
          <p class="mb-8 leading-relaxed">
            eggモデルで勝ち得た子役の座を17年間引きずってます。ギリ飯食えてますyo。
          </p>
        </div>
      </div>
    </div>
</section>
