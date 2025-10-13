# Argo Workflows Gallery

### Filter Notebooks by Tags
<div id="tag-filter" style="margin:10px 0 20px 0;">
  <input type="text" id="tagInput" placeholder="type tags…" 
         style="width:100%;max-width:420px;padding:8px;border:1px solid #cddff1;border-radius:6px;">
</div>

<div id="gallery" style="display:flex;flex-direction:column;gap:20px;max-width:900px;">
<div class="notebook-card" data-tags="" style="display:flex;align-items:flex-start;border:1px solid #cddff1;border-radius:6px;padding:14px 20px;background:#f9fbfe;box-shadow:1px 1px 4px #dfeaf5;">
  <div style="width:120px;height:90px;flex-shrink:0;display:flex;align-items:center;justify-content:center;background:#fff;border:1px solid #e0eaf5;border-radius:6px;overflow:hidden;margin-right:24px;">
    <img src="" alt="Thumbnail" style="max-width:100%;max-height:100%;object-fit:contain;">
  </div>
  <div style="flex:1;">
    <strong>Untitled</strong><br>
    <div style="margin:4px 0 8px 0;">no description</div>
    <div style="margin:6px 0 10px 0;"></div>
    <a href="../../../../../../.." style="text-decoration:none;color:#1d70b8;font-weight:bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="" style="display:flex;align-items:flex-start;border:1px solid #cddff1;border-radius:6px;padding:14px 20px;background:#f9fbfe;box-shadow:1px 1px 4px #dfeaf5;">
  <div style="width:120px;height:90px;flex-shrink:0;display:flex;align-items:center;justify-content:center;background:#fff;border:1px solid #e0eaf5;border-radius:6px;overflow:hidden;margin-right:24px;">
    <img src="" alt="Thumbnail" style="max-width:100%;max-height:100%;object-fit:contain;">
  </div>
  <div style="flex:1;">
    <strong>Untitled</strong><br>
    <div style="margin:4px 0 8px 0;">no description</div>
    <div style="margin:6px 0 10px 0;"></div>
    <a href="../../../../../../.." style="text-decoration:none;color:#1d70b8;font-weight:bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="" style="display:flex;align-items:flex-start;border:1px solid #cddff1;border-radius:6px;padding:14px 20px;background:#f9fbfe;box-shadow:1px 1px 4px #dfeaf5;">
  <div style="width:120px;height:90px;flex-shrink:0;display:flex;align-items:center;justify-content:center;background:#fff;border:1px solid #e0eaf5;border-radius:6px;overflow:hidden;margin-right:24px;">
    <img src="" alt="Thumbnail" style="max-width:100%;max-height:100%;object-fit:contain;">
  </div>
  <div style="flex:1;">
    <strong>Untitled</strong><br>
    <div style="margin:4px 0 8px 0;">no description</div>
    <div style="margin:6px 0 10px 0;"></div>
    <a href="../../../../../../.." style="text-decoration:none;color:#1d70b8;font-weight:bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="" style="display:flex;align-items:flex-start;border:1px solid #cddff1;border-radius:6px;padding:14px 20px;background:#f9fbfe;box-shadow:1px 1px 4px #dfeaf5;">
  <div style="width:120px;height:90px;flex-shrink:0;display:flex;align-items:center;justify-content:center;background:#fff;border:1px solid #e0eaf5;border-radius:6px;overflow:hidden;margin-right:24px;">
    <img src="" alt="Thumbnail" style="max-width:100%;max-height:100%;object-fit:contain;">
  </div>
  <div style="flex:1;">
    <strong>Untitled</strong><br>
    <div style="margin:4px 0 8px 0;">no description</div>
    <div style="margin:6px 0 10px 0;"></div>
    <a href="../../.." style="text-decoration:none;color:#1d70b8;font-weight:bold;">View Notebook</a>
  </div>
</div>
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