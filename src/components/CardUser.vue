<template>
  <div>
    <div class="mx-auto px-1">
      <div class="md:flex bg-white rounded-lg p-6">
    <div class="h-16 w-16 md:h-24 md:w-24 mx-auto md:mx-0 md:mr-6">
      <vs-avatar size="70" badge badge-color="success" history history-gradient circle class="px-1 py-1">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcRTBrxgTsgMlNM4yvjvWZyaZxlJ-tZadZwuaBaLSW9K4qzr12Cg&usqp=CAU" alt="">
      </vs-avatar>
    </div>
    <div class="px-6 py-4">
      <div class="font-bold text-xl mb-2">The Coldest Sunset</div>
      <p class="text-gray-700 text-base">
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus quia, nulla! Maiores et perferendis eaque, exercitationem praesentium nihil.
      </p>
    </div>
  </div>
    </div>
    <div class="mx-auto px-1">
      <div class="md:flex bg-white rounded-lg p-6">
        <div class="h-16 w-16 md:h-24 md:w-24 mx-auto md:mx-0 md:mr-6">
          <vs-avatar size="70" badge badge-color="success" history history-gradient circle class="px-1 py-1">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcRTBrxgTsgMlNM4yvjvWZyaZxlJ-tZadZwuaBaLSW9K4qzr12Cg&usqp=CAU" alt="">
          </vs-avatar>
        </div>
        <div class="px-6 py-4">
          <div class="font-bold text-xl mb-2">The Coldest Sunset</div>
          <p class="text-gray-700 text-base">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus quia, nulla! Maiores et perferendis eaque, exercitationem praesentium nihil.
          </p>
        </div>
        <div class="px-6 py-4">
          <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2">
             <vs-switch v-model="active4">
            <template #on>
              Admin
            </template>
            <template #off>
              Default
            </template>
          </vs-switch>
          </span>
          <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2"> <vs-checkbox v-model="option">
        Option
      </vs-checkbox></span>
          <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700">#winter</span>
          <vs-switch v-model="active4">
            <template #on>
              Admin
            </template>
            <template #off>
              Default
            </template>
          </vs-switch>
          <vs-checkbox v-model="option">
            Option
          </vs-checkbox>
        </div>
      </div>
    </div>

    <div class="md-flex rounded shadow-lg bg-white p-6">
      <div class="px-6 py-2">
        <vs-avatar size="70" badge badge-color="success" history history-gradient circle class="px-1 py-1">
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcRTBrxgTsgMlNM4yvjvWZyaZxlJ-tZadZwuaBaLSW9K4qzr12Cg&usqp=CAU" alt="">
        </vs-avatar>
      </div>
      <div class="px-6 py-4">
        <div class="font-bold text-xl mb-2">The Coldest Sunset</div>
        <p class="text-gray-700 text-base">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus quia, nulla! Maiores et perferendis eaque, exercitationem praesentium nihil.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'CardUser',
  data: () => ({
    active1: true,
    active2: false,
    active3: false,
    active4: true,
    active5: true
  })
}
</script>

<style scoped>

</style>
