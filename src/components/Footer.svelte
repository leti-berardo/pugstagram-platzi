<script>
  let year = new Date().getFullYear();
</script>

<style>
  .Footer .Footer-content p span.copyleft {
    display: inline-block;
    text-align: right;
    margin: 0px;
    -moz-transform: scaleX(-1);
    -o-transform: scaleX(-1);
    -webkit-transform: scaleX(-1);
    transform: scaleX(-1);
    filter: FlipH;
    -ms-filter: “FlipH”;
  }

  .Footer {
    font-size: 11px;
    letter-spacing: 1px;
    font-weight: normal;
    color: #c7c7c7;
  }
</style>

<div class="Footer">
  <div class="Footer-content">
    <div class="Footer-copy">
      <p>
        <span class="copyleft">©</span>
        {year} Berlinstagram from Platzi
      </p>
    </div>
  </div>
</div>
