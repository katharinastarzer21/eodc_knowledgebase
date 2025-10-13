# GFM Gallery

### Filter Notebooks by Tags
<div id="tag-filter" style="margin:10px 0 20px 0;">
  <input type="text" id="tagInput" placeholder="type tags…" 
         style="width:100%;max-width:420px;padding:8px;border:1px solid #cddff1;border-radius:6px;">
</div>

<div id="gallery" style="display:flex;flex-direction:column;gap:20px;max-width:900px;">
<div class="notebook-card" data-tags="GFM" style="display:flex;align-items:flex-start;border:1px solid #cddff1;border-radius:6px;padding:14px 20px;background:#f9fbfe;box-shadow:1px 1px 4px #dfeaf5;">
  <div style="width:120px;height:90px;flex-shrink:0;display:flex;align-items:center;justify-content:center;background:#fff;border:1px solid #e0eaf5;border-radius:6px;overflow:hidden;margin-right:24px;">
    <img src="https://european-flood.emergency.copernicus.eu/efas_frontend/assets/img/wms/GFM.svg" alt="Thumbnail" style="max-width:100%;max-height:100%;object-fit:contain;">
  </div>
  <div style="flex:1;">
    <strong>Save GFM results in cloud object store</strong><br>
    <div style="margin:4px 0 8px 0;">In this demo we will show you how to remotely process data on the EODC cluster using dask and save the result in a cloud object store.</div>
    <div style="margin:6px 0 10px 0;"><span class="tag" style="display:inline-block;margin-right:6px;padding:2px 8px;border:1px solid #ccd9ea;border-radius:999px;font-size:12px;">GFM</span></div>
    <a href="gfm_dask_objectstorage.ipynb" style="text-decoration:none;color:#1d70b8;font-weight:bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="GFM filter" style="display:flex;align-items:flex-start;border:1px solid #cddff1;border-radius:6px;padding:14px 20px;background:#f9fbfe;box-shadow:1px 1px 4px #dfeaf5;">
  <div style="width:120px;height:90px;flex-shrink:0;display:flex;align-items:center;justify-content:center;background:#fff;border:1px solid #e0eaf5;border-radius:6px;overflow:hidden;margin-right:24px;">
    <img src="https://european-flood.emergency.copernicus.eu/efas_frontend/assets/img/wms/GFM.svg" alt="Thumbnail" style="max-width:100%;max-height:100%;object-fit:contain;">
  </div>
  <div style="flex:1;">
    <strong>Refine STAC query using filters</strong><br>
    <div style="margin:4px 0 8px 0;">In this notebook, we demonstrate how to refine the query against the GFM STAC catalogue using the filter STAC API extension</div>
    <div style="margin:6px 0 10px 0;"><span class="tag" style="display:inline-block;margin-right:6px;padding:2px 8px;border:1px solid #ccd9ea;border-radius:999px;font-size:12px;">GFM</span><span class="tag" style="display:inline-block;margin-right:6px;padding:2px 8px;border:1px solid #ccd9ea;border-radius:999px;font-size:12px;">filter</span></div>
    <a href="gfm_filter.ipynb" style="text-decoration:none;color:#1d70b8;font-weight:bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="GFM DASK" style="display:flex;align-items:flex-start;border:1px solid #cddff1;border-radius:6px;padding:14px 20px;background:#f9fbfe;box-shadow:1px 1px 4px #dfeaf5;">
  <div style="width:120px;height:90px;flex-shrink:0;display:flex;align-items:center;justify-content:center;background:#fff;border:1px solid #e0eaf5;border-radius:6px;overflow:hidden;margin-right:24px;">
    <img src="https://european-flood.emergency.copernicus.eu/efas_frontend/assets/img/wms/GFM.svg" alt="Thumbnail" style="max-width:100%;max-height:100%;object-fit:contain;">
  </div>
  <div style="flex:1;">
    <strong>EODC Dask Tutorial</strong><br>
    <div style="margin:4px 0 8px 0;">In this notebook we demonstrate the basics of using Dask on the EODC cluster.</div>
    <div style="margin:6px 0 10px 0;"><span class="tag" style="display:inline-block;margin-right:6px;padding:2px 8px;border:1px solid #ccd9ea;border-radius:999px;font-size:12px;">GFM</span><span class="tag" style="display:inline-block;margin-right:6px;padding:2px 8px;border:1px solid #ccd9ea;border-radius:999px;font-size:12px;">DASK</span></div>
    <a href="gfm_maximum_flood_extent_dask.ipynb" style="text-decoration:none;color:#1d70b8;font-weight:bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="GFM STAC" style="display:flex;align-items:flex-start;border:1px solid #cddff1;border-radius:6px;padding:14px 20px;background:#f9fbfe;box-shadow:1px 1px 4px #dfeaf5;">
  <div style="width:120px;height:90px;flex-shrink:0;display:flex;align-items:center;justify-content:center;background:#fff;border:1px solid #e0eaf5;border-radius:6px;overflow:hidden;margin-right:24px;">
    <img src="https://european-flood.emergency.copernicus.eu/efas_frontend/assets/img/wms/GFM.svg" alt="Thumbnail" style="max-width:100%;max-height:100%;object-fit:contain;">
  </div>
  <div style="flex:1;">
    <strong>GFM maximum flood extent with STAC</strong><br>
    <div style="margin:4px 0 8px 0;">This notebook will demonstrate how to find data using STAC, load it into a xarray object and calculate a result.</div>
    <div style="margin:6px 0 10px 0;"><span class="tag" style="display:inline-block;margin-right:6px;padding:2px 8px;border:1px solid #ccd9ea;border-radius:999px;font-size:12px;">GFM</span><span class="tag" style="display:inline-block;margin-right:6px;padding:2px 8px;border:1px solid #ccd9ea;border-radius:999px;font-size:12px;">STAC</span></div>
    <a href="gfm_maximum_flood_extent_local.ipynb" style="text-decoration:none;color:#1d70b8;font-weight:bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="GFM STAC" style="display:flex;align-items:flex-start;border:1px solid #cddff1;border-radius:6px;padding:14px 20px;background:#f9fbfe;box-shadow:1px 1px 4px #dfeaf5;">
  <div style="width:120px;height:90px;flex-shrink:0;display:flex;align-items:center;justify-content:center;background:#fff;border:1px solid #e0eaf5;border-radius:6px;overflow:hidden;margin-right:24px;">
    <img src="https://european-flood.emergency.copernicus.eu/efas_frontend/assets/img/wms/GFM.svg" alt="Thumbnail" style="max-width:100%;max-height:100%;object-fit:contain;">
  </div>
  <div style="flex:1;">
    <strong>Computation of GFM Maximum Flood Extent for a specific area and time of interest</strong><br>
    <div style="margin:4px 0 8px 0;">With this notebook we demonstrate how STAC can be used to find GFM data (ensemble_flood_extent) and derive the maximum flood extent from it.</div>
    <div style="margin:6px 0 10px 0;"><span class="tag" style="display:inline-block;margin-right:6px;padding:2px 8px;border:1px solid #ccd9ea;border-radius:999px;font-size:12px;">GFM</span><span class="tag" style="display:inline-block;margin-right:6px;padding:2px 8px;border:1px solid #ccd9ea;border-radius:999px;font-size:12px;">STAC</span></div>
    <a href="gfm_maximum_flood_extent_simple_plot.ipynb" style="text-decoration:none;color:#1d70b8;font-weight:bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="GFM STAC" style="display:flex;align-items:flex-start;border:1px solid #cddff1;border-radius:6px;padding:14px 20px;background:#f9fbfe;box-shadow:1px 1px 4px #dfeaf5;">
  <div style="width:120px;height:90px;flex-shrink:0;display:flex;align-items:center;justify-content:center;background:#fff;border:1px solid #e0eaf5;border-radius:6px;overflow:hidden;margin-right:24px;">
    <img src="https://european-flood.emergency.copernicus.eu/efas_frontend/assets/img/wms/GFM.svg" alt="Thumbnail" style="max-width:100%;max-height:100%;object-fit:contain;">
  </div>
  <div style="flex:1;">
    <strong>Compute maximum flood extent utilizing STAC</strong><br>
    <div style="margin:4px 0 8px 0;">With this notebook, we want to demo how STAC can be used to find GFM ensemble_flood_extent data and derive the maximum flood extent from it.</div>
    <div style="margin:6px 0 10px 0;"><span class="tag" style="display:inline-block;margin-right:6px;padding:2px 8px;border:1px solid #ccd9ea;border-radius:999px;font-size:12px;">GFM</span><span class="tag" style="display:inline-block;margin-right:6px;padding:2px 8px;border:1px solid #ccd9ea;border-radius:999px;font-size:12px;">STAC</span></div>
    <a href="gfm_maximum_flood_extent_stac.ipynb" style="text-decoration:none;color:#1d70b8;font-weight:bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="GFM" style="display:flex;align-items:flex-start;border:1px solid #cddff1;border-radius:6px;padding:14px 20px;background:#f9fbfe;box-shadow:1px 1px 4px #dfeaf5;">
  <div style="width:120px;height:90px;flex-shrink:0;display:flex;align-items:center;justify-content:center;background:#fff;border:1px solid #e0eaf5;border-radius:6px;overflow:hidden;margin-right:24px;">
    <img src="https://european-flood.emergency.copernicus.eu/efas_frontend/assets/img/wms/GFM.svg" alt="Thumbnail" style="max-width:100%;max-height:100%;object-fit:contain;">
  </div>
  <div style="flex:1;">
    <strong>Plot GFM flood scene</strong><br>
    <div style="margin:4px 0 8px 0;">This tutorial will show how to plot a part of a flooded GFM scene using an OpenStreetMap basemap as background.</div>
    <div style="margin:6px 0 10px 0;"><span class="tag" style="display:inline-block;margin-right:6px;padding:2px 8px;border:1px solid #ccd9ea;border-radius:999px;font-size:12px;">GFM</span></div>
    <a href="gfm_plot_flood_scene.ipynb" style="text-decoration:none;color:#1d70b8;font-weight:bold;">View Notebook</a>
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