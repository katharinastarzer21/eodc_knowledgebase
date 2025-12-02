# CSW Gallery

### Filter Notebooks by Tags
<div id="tag-filter" style="margin:10px 0 20px 0;">
  <input type="text" id="tagInput" placeholder="type tags…" 
         style="width:100%;max-width:420px;padding:8px;border:1px solid #cddff1;border-radius:6px;">
</div>

<div id="gallery" style="display:flex;flex-direction:column;gap:20px;max-width:900px;">

</div>

<script>
// simpler AND-Filter
const input = document.getElementById('tagInput');
const cards = Array.from(document.querySelectorAll('.notebook-card'));
input.addEventListener('input', () => {
  const q = input.value.trim().toLowerCase().split(/\s+/).filter(Boolean);
  cards.forEach(c => {
    const tags = (c.getAttribute('data-tags') || '').toLowerCase().split(/\s+/).filter(Boolean);
    const match = q.every(t => tags.includes(t));
    c.style.display = match ? 'flex' : 'none';
  });
});
</script>