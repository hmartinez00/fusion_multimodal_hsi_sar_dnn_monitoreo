Procedo a redactar el prompt de ingeniería de imágenes completamente optimizado para **`fig3.png`**.

Este prompt traduce de forma explícita la degradación gradual del rendimiento de los algoritmos competidores en comparación con tu propuesta (siguiendo los datos reales de la Tabla 4) e implementa la segmentación diagonal del terreno (agrícola vs. urbano complejo) sin añadir texto incrustado, cumpliendo estrictamente con el estándar IEEE.

### PROMPT DE IMAGEN OPTIMIZADO (Científicamente Riguroso):

```json
A 2D technical vector diagram, multi-panel remote sensing comparison schematic, flat design, minimalist, background in pure white, arranged in a strict horizontal 1x5 grid layout of five identical square panels separated by subtle white margins. The image contains NO embedded text or labels.

Panel 1 (Far Left - Multimodal Reference): A stylized false-color satellite image mosaic combining dark technical grey #4A4A4A lines (representing SAR radar structural backscatter) and sharp cobalt blue #0047AB shades (representing HSI hyperspectral bands), illustrating a raw fused input scene with diagonal division: large clean geometric blocks on the top-half (agricultural fields) and dense, complex fractal patterns on the bottom-half (coastal urban area).

Panel 2 (Second - Ground Truth): A perfect, noise-free semantic segmentation reference map of the same scene. Utilizes a clean, solid, flat color palette for the 7 land cover classes: olive green for large fields, light grey for roads, muted blue for water bodies, and beige for urban structures. Boundaries between all regions are perfectly sharp, geometric, and continuous.

Panel 3 (Third - Proposed Method): A highly accurate reconstruction of the Ground Truth (Panel 2), achieving 94% visual fidelity. The geometric boundaries of the upper agricultural fields are flawlessly crisp, and the intricate bottom urban filaments are perfectly continuous and sharply defined, showing maximum robustness against noise and no pixel artifacts.

Panel 4 (Fourth - Liu et al. NCDFF): The same semantic map but with visible intermediate degradation. The large agricultural fields in the top-half remain mostly homogeneous, but the crisp boundaries between classes show an over-smoothed, blurred, or wavy appearance. The complex urban structures at the bottom show slight disconnections and minor bleeding into adjacent classes.

Panel 5 (Fifth - Li et al. Asymmetric): The same semantic map with high degradation reflecting lower performance. The large agricultural fields in the top-half are heavily corrupted by a noticeable 'salt-and-pepper' noise effect (scattered individual pixels of incorrect random colors). The boundaries between all regions are highly pixelated, and the fine bottom urban lines are fragmented into isolated clusters, illustrating vulnerability to spectral mixing.

Each panel is bordered by a very thin, light grey frame. The entire 1x5 grid flows logically from left to right, showcasing a precise scientific progression of visual accuracy, matching IEEE publication style.

```