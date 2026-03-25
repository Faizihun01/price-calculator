// Calculation logic for Moon's Calculator
document.addEventListener('DOMContentLoaded', function () {
  const rateEl = document.getElementById('rate');
  const rentalEl = document.getElementById('rental');
  const widthEl = document.getElementById('width');
  const heightEl = document.getElementById('height');
  const lengthEl = document.getElementById('length');
  const calcBtn = document.getElementById('calculateBtn');
  const measureEl = document.getElementById('measure');
  const totalEl = document.getElementById('total');

  function parseNumber(el) {
    const raw = (el.value || '').toString().trim();
    if (raw === '') return 0; // treat empty fields as 0
    const v = parseFloat(raw);
    return Number.isFinite(v) ? v : NaN;
  }

  calcBtn.addEventListener('click', function () {
    const rate = parseNumber(rateEl);
    const rental = parseNumber(rentalEl);
    const w = parseNumber(widthEl);
    const h = parseNumber(heightEl);
    const l = parseNumber(lengthEl);

    // If any field contains non-numeric input, stop and show a message.
    if ([rate, rental, w, h, l].some(x => !Number.isFinite(x))) {
      alert('Please enter valid numbers (or leave blank to use 0).');
      return;
    }

    // Allow zero dimensions, but disallow negative values.
    if (w < 0 || h < 0 || l < 0) {
      alert('Dimensions cannot be negative.');
      return;
    }

    const measure = w * h * l; // cubic inches
    const total = ((rate + rental) / 2400) * measure; // result in PKR (Rs)

    measureEl.textContent = Number.isFinite(measure)
      ? measure.toLocaleString(undefined, {maximumFractionDigits:4}) + ' in³'
      : '—';

    // Format the total as Pakistani rupees with 'Rs' prefix
    totalEl.textContent = Number.isFinite(total)
      ? 'Rs ' + total.toLocaleString(undefined, {maximumFractionDigits:2})
      : '—';

    // Add a subtle animation when showing results
    totalEl.classList.add('flash');
    setTimeout(() => totalEl.classList.remove('flash'), 400);
  });
});
