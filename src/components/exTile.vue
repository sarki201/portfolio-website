<template>
  <div
    class="grid grid-cols-1 sm:grid-cols-[50px,1fr] lg:grid-cols-[200px,50px,1fr] gap-y-4 sm:gap-4"
  >
    <p class="text-accent lg:text-right pt-2 lg:col-span-1 col-start-2">{{
      date
    }}</p>
    <div
      class="sm:flex flex-col items-center hidden row-start-1 row-end-3 lg:row-start-auto lg:row-end-auto lg:col-span-1"
    >
      <div class="rounded-full bg-accent p-3">
        <svg
          class="fill-main-dark"
          version="1.0"
          id="Layer_1"
          xmlns="http://www.w3.org/2000/svg"
          xmlns:xlink="http://www.w3.org/1999/xlink"
          width="26px"
          height="26px"
          viewBox="0 0 64 64"
          enable-background="new 0 0 64 64"
          xml:space="preserve"
        >
          <path
            d="M32,0C18.746,0,8,10.746,8,24c0,5.219,1.711,10.008,4.555,13.93c0.051,0.094,0.059,0.199,0.117,0.289l16,24
	C29.414,63.332,30.664,64,32,64s2.586-0.668,3.328-1.781l16-24c0.059-0.09,0.066-0.195,0.117-0.289C54.289,34.008,56,29.219,56,24
	C56,10.746,45.254,0,32,0z M32,32c-4.418,0-8-3.582-8-8s3.582-8,8-8s8,3.582,8,8S36.418,32,32,32z"
          />
        </svg>
      </div>
      <div class="w-1 bg-accent flex-1"></div>
    </div>
    <div
      class="bg-main-dark drop-shadow-xl border-solid border-b-[5px] border-accent border-opacity-100 p-4 text-main mb-8 col-start-2 lg:col-span-1"
    >
      <h3 class="text-[25px] mb-4">{{ employer }}</h3>
      <h4 class="text-[20px] mb-2">{{ title }}</h4>
      <ul class="list-disc pl-4">
        <li class="mb-2">
          <p>
            {{ description1 }}
          </p>
        </li>
        <li class="mb-2">
          <p>
            {{ description2 }}
          </p>
        </li>
        <li class="">
          <p>
            {{ description3 }}
          </p>
        </li>
      </ul>
    </div>
  </div>
</template>
<script>
export default {
  name: "exTile",
  props: {
    title: {
      type: String,
      required: true,
    },
    employer: {
      type: String,
      required: true,
    },
    date: {
      type: String,
      required: true,
    },
    exLink: {
      type: String,
      required: false,
    },
    description1: {
      type: String,
      required: true,
    },
    description2: {
      type: String,
      required: true,
    },
    description3: {
      type: String,
      required: true,
    },
  },
};
</script>
