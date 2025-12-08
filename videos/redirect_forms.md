<script>
  window.onload = function() {
    var urls = [
      "https://forms.office.com/r/s3DrLvRS4j",
      "https://forms.office.com/r/s5uWkEdafr",
      "https://forms.office.com/r/CmYqNMxsjL"，
      "https://forms.office.com/r/7KU8LAMuR4"，
      "https://forms.office.com/r/Jbs2jjwcpx"，
      "https://forms.office.com/r/RzpWGk2k9W"
    ];
    var randomUrl = urls[Math.floor(Math.random() * urls.length)];
    window.location.href = randomUrl;
  };
</script>
