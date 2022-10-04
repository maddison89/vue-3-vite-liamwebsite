<template>
  <div class="bg-white py-12">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
      <div class="lg:text-center">
        <h2 class="text-lg font-semibold text-indigo-600">Transactions</h2>
        <p class="mt-2 text-3xl font-bold leading-8 tracking-tight text-gray-900 sm:text-4xl">A better way to send money</p>
        <p class="mt-4 max-w-2xl text-xl text-gray-500 lg:mx-auto">Lorem ipsum dolor sit amet consect adipisicing elit. Possimus magnam voluptatum cupiditate veritatis in accusamus quisquam.</p>
      </div>

      <div class="mt-10">
        <dl class="space-y-10 md:grid md:grid-cols-2 md:gap-x-8 md:gap-y-10 md:space-y-0">
          <div v-for="feature in features" :key="feature.name" class="relative">
            <dt>
              <div class="absolute flex h-12 w-12 items-center justify-center rounded-md bg-indigo-500 text-white">
                icon
              </div>
              <p class="ml-16 text-lg font-medium leading-6 text-gray-900">{{ feature.name }}</p>
            </dt>
            <dd class="mt-2 ml-16 text-base text-gray-500">{{ feature.description }}</dd>
          </div>
        </dl>
      </div>
    </div>
  </div>
</template>

<script setup>
const features = [
  {
    name: 'Competitive exchange rates',
    description:
      'Lorem ipsum, dolor sit amet consectetur adipisicing elit. Maiores impedit perferendis suscipit eaque, iste dolor cupiditate blanditiis ratione.',
  },
  {
    name: 'No hidden fees',
    description:
      'Lorem ipsum, dolor sit amet consectetur adipisicing elit. Maiores impedit perferendis suscipit eaque, iste dolor cupiditate blanditiis ratione.',
  },
  {
    name: 'Transfers are instant',
    description:
      'Lorem ipsum, dolor sit amet consectetur adipisicing elit. Maiores impedit perferendis suscipit eaque, iste dolor cupiditate blanditiis ratione.',
  },
  {
    name: 'Mobile notifications',
    description:
      'Lorem ipsum, dolor sit amet consectetur adipisicing elit. Maiores impedit perferendis suscipit eaque, iste dolor cupiditate blanditiis ratione.',
  },
]
</script>