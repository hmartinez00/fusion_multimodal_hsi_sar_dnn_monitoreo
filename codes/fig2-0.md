Procedo a redactar el prompt técnico y de alta precisión científica para la generación de **`fig2.png`**.

Este prompt ha sido diseñado para subsanar todas las discrepancias detectadas, integrando el pipeline de preprocesamiento, la granularidad de las tres escalas fijas y la retropropagación de la función de pérdida compuesta, todo bajo la estricta estética IEEE sin texto incrustado.

### PROMPT DE IMAGEN MEJORADO (Científicamente Preciso):

```json
A 2D technical vector diagram, engineered schematic, flat design, minimalist, background in pure white, utilizing a strict color palette of cobalt blue #0047AB and technical grey #4A4A4A. The image contains NO embedded text.

The diagram illustrates the proposed Deep HSI-SAR Multimodal Fusion Architecture (fig2.png), flowing from left to right.

Region 1 (Far Left, Data & Preprocessing): Two vertical aligned source blocks. Upper (Cobalt Blue HSI) with segmented spectral λ symbol layers, connecting to a sub-block schematic of PCA (99%) operator and normalizer. Lower (Technical Grey SAR) with wavy line radar schematic, connecting to a sub-block schematic of 'Lee refined' speckle filtering grid and logarithmic curve. Both preprocess blocks flow into a central anchor node of Co-registration (geometric shape).

Region 2 (Center-Left, Multi-scale Feature Extractors): From the anchor node, the flow bifurcates into two horizontal parallel branches. Upper Branch (HSI, Blue, with schematic Conv 1D + Res2D icons) is subdivided into three stacked horizontal levels, decreasing in height (labeled by overpic as 1x, 1/2, 1/4) showing internal pooling lines. Lower Branch (SAR, Grey, with textural + Long-range Attention icons) is also subdivided into three stacked horizontal levels, decreasing in height (1x, 1/2, 1/4) showing internal pooling lines.

Region 3 (Center, Asymmetric Cross-Attention Fusion Core): A central large cluster of concentric circles and matrix grid patterns. Lines from all 3 HSI scales and all 3 SAR scales intersect this core with crossed 'X' bidirectional attention vectors. Within this core, a small stylized icon of 8 parallel matrix stacks symbolizes the 8 Attention Heads. Vectors are asymmetric; the main flow from HSI scale lines (Queries Q) is continuous, while the complimentary flow from SAR scale lines (Keys K, Values V) is thinner or slightly dashed, illustrating a lighter, asymmetrical bidirectionality.

Region 4 (Right & Loss Flow, Decoder & Output): The fused core consolidates into a single line flowing to a 'Decoder' block. This decoder projects the final segmented Land Cover Map output. From this final map block, a dashed backpropagation vector line splits and runs back along the top and bottom of the whole diagram, distributing distinct, multifaced penalty nodes: one flows into the attention core (Consistency Loss), one flows back to intermediate extractor branches (Auxiliary Reconstruction Loss), and one connects to the main final map (Cross-Entropy Loss), illustrating the complex gradient optimization flow.

Clean vector lines (1pt or 1.5pt), technical symbols, and minimalist deep learning icons are used throughout, creating a professional, complex IEEE schematic. All text is removed; labels and mathematical variables will be added via overpic in LaTeX.

```