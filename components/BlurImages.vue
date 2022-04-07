<!-- Please remove this file from your project -->
<template>
  <div
    class="relative flex items-top justify-center min-h-screen bg-gray-100 sm:items-center sm:pt-0"
  >
    <div class="max-w-4xl mx-auto sm:px-6 lg:px-8">
      <h1 class="text-center mt-10 text-3xl leading-9 font-extrabold text-gray-900">
        Blur Faces in Images in Nuxt
      </h1>
      <div class="mt-8 bg-white overflow-hidden shadow sm:rounded-lg p-6">
        <cld-image public-id="/samples/people/group-picture-3.jpg">
          <cld-transformation effect="pixelate_faces" />
        </cld-image>
      </div>
      <div class="mt-8 bg-white overflow-hidden shadow sm:rounded-lg p-6">
        <cld-image public-id="/samples/people/group-picture.jpg">
          <cld-transformation effect="pixelate_faces:9" />
        </cld-image>
      </div>
      <div class="mt-8 bg-white overflow-hidden shadow sm:rounded-lg p-6">
        <cld-image public-id="/samples/people/group-picture-2.jpg">
          <cld-transformation effect="pixelate_faces:5" />
        </cld-image>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "BlurImages",
};
</script>
