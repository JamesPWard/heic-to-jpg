<template>
  <div>
    <div class="input-group">
      <div class="input-group-prepend">
        <span class="input-group-text" id="inputGroupFileAddon01">Upload</span>
      </div>
      <div class="custom-file">
        <input type="file" class="custom-file-input" id="inputGroupFile01"
          aria-describedby="inputGroupFileAddon01" multiple>
        <label class="custom-file-label" for="inputGroupFile01">Choose file</label>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Uploader',
  props: {
    msg: String
  }
}
</script>