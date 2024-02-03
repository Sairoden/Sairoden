<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/Sairoden/Sairoden/assets/72735313/25c3090a-fb83-4c18-bc24-7e1f11fb2ca1" alt="Dark Mode" id="dark-mode-image">
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/Sairoden/Sairoden/assets/72735313/4cd1b9dc-ebea-4a7d-a997-3651c8162f6a" alt="Light Mode" id="light-mode-image">
</picture>


# Dynamic GitHub README

<div align="center">
  <img src="https://github.com/Sairoden/Sairoden/assets/72735313/022e72bc-f6da-4110-994a-e5f2c137d4c8" alt="Light Mode" id="light-mode-image">
  <img src="https://github.com/Sairoden/Sairoden/assets/72735313/0f0fb479-1b89-4cb5-affb-1cd8232e7f57" alt="Dark Mode" id="dark-mode-image">
</div>

<!-- Add a script to dynamically change image based on theme -->
<script>
  const prefersDark = window.matchMedia && window.matchMedia('(prefers-color-scheme: dark)').matches;

  const lightModeImage = document.getElementById('light-mode-image');
  const darkModeImage = document.getElementById('dark-mode-image');

  if (prefersDark) {
    // Set dark mode image
    lightModeImage.style.display = 'none';
    darkModeImage.style.display = 'block';
  } else {
    // Set light mode image
    lightModeImage.style.display = 'block';
    darkModeImage.style.display = 'none';
  }
</script>
