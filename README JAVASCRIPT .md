const toggleBtn = document.getElementById('toggle-btn');
const extraInfo = document.getElementById('extra-info');

toggleBtn.addEventListener('click', () => {
  if (extraInfo.classList.contains('hidden')) {
    extraInfo.classList.remove('hidden');
    toggleBtn.textContent = 'Show Less Info';
  } else {
    extraInfo.classList.add('hidden');
    toggleBtn.textContent = 'Show More Info';
  }
});
