<template>
  <div class="section" id="input">
    <h2>File Info</h2>
    <span class="row"
      ><label
        >Input File: <input type="file" name="input_file" accept=".pdf" id="input_file" /></label
    ></span>
    <!-- <span class="row"><label>Page Size: <span id="page_size"></span></span> -->
    <!-- <span class="row">Page Ratio: <span id="input_ratio"></span></span> -->
    <span class="row" style="padding: 10px; font-style: italic"
      >While some PDF viewers display the first two pages as a spread, be aware the first page,
      which is odd, will be on the right when printed. The first printed spread are pages 2 & 3 of
      your PDF document. Evens always on the left, odds always on the right.</span
    >
    <span class="row"
      ><label for="print_file">Generated Files</label>
      <select name="print_file" id="print_file">
        <option value="aggregated">Aggregated File Only</option>
        <option value="both" selected>Both aggregated & per signature files</option>
        <option value="signatures">Signature Files Only</option>
      </select>
    </span>
  </div>
</template>
