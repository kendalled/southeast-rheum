<template>
    <span class="font-semibold tracking-wide text-teal-600 uppercase">
      {{ text }}
    </span>
  </template>
  
  <script>
  export default {
    name: 'SubText',
    props: {
      text: {
        type: String,
        required: true,
        default: 'get started'
      }
    }
  }
  </script>
  