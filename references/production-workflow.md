# Production Workflow

Use this workflow for every source image. Its budgets and stop conditions convert the skill's aesthetic principles into observable production decisions. They are ceilings and gates, not stylistic targets.

## 1. Write the construction contract

Before generation, record:

1. primary subject and source-appropriate orthographic view;
2. primitive inventory for each important local whole;
3. genuine symmetry, radial, repeating, alternating, grid, or modular rule;
4. construction operations such as alignment, overlap, tangency, mirroring, intersection, subtraction, rotation, and scale;
5. locked middle-to-bottom transformation map;
6. shape budget and explicit deletion list.

Do not generate when any item is missing. The deletion list must name concrete photographic information to remove, such as fur tufts, individual leaflets beyond the selected rhythm, tile ends beyond representative modules, bark texture, paving seams, distant windows, debris, or repeated flowers.

## 2. Set a shape budget

Choose the closest source class and adapt only when structural identity genuinely requires it:

| Source class | Primary masses | Secondary shapes | Repeated modules | Background |
|---|---:|---:|---:|---:|
| Simple single object | 3-5 | 4-10 | 0-5 per family | 1-2 regions, 0-3 axes |
| Animal or person | 4-7 | 8-16 | 2-6 per family | 1-3 regions, 1-4 axes |
| Plant, radial, or repeated organic subject | 3-6 major structures | 6-14 | 5-12 per major rhythm | 1-3 regions, 0-4 axes |
| Architecture or modular structure | 4-8 major planes | 8-18 | 3-7 representative modules per family | 1-3 regions, 1-5 axes |
| Multi-subject interaction | 4-7 masses per principal subject, then consolidate | 8-16 shared structural divisions | 2-6 per family | 1-3 regions, 1-4 axes |

Treat these values as maximum complexity before a source-specific justification. Do not fill a budget merely because capacity remains. When the source exceeds the budget, preserve identity-bearing relationships and consolidate repeated or low-value information.

Prompts must state the chosen numbers and name what is omitted. Avoid vague instructions such as "simplify the background" without a region or axis limit.

## 3. Generate in stages

### Stage A: geometric master

Generate only the middle-panel construction first whenever the tool supports it. Use the selected orthographic view, visible standard primitives, exact shape budget, deletion list, subject integrity envelope, and outline-only material rule.

Review the master before any coloring. Reject it if it reads as an edge trace, detailed illustration, coloring-book outline, or generic icon.

### Stage B: locked color reconstruction

Use the approved geometric master as the required reference. Preserve every outer contour, internal division, overlap boundary, module, and negative-space boundary. Only remove black lines and assign source-related flat color fields.

Prefer a template-preserving edit or deterministic closed-region coloring. If the available generator cannot preserve the template reliably, generate the middle and bottom together as a registered pair and reject any mismatch. Do not claim exact registration when visible boundaries differ.

### Stage C: deterministic assembly

Whenever practical, assemble the final 2:3 canvas with deterministic image operations:

- top: the actual source photograph, proportionally scaled and safely cropped or fitted;
- middle: approved outline-only geometric master;
- bottom: approved contourless color reconstruction.

Do not route the original photograph through generation merely to create the final stack. Use generation for the transformed panels and deterministic assembly for dimensions, panel boundaries, and source preservation.

A one-pass three-panel generation is a fallback only when staged references, edits, or deterministic assembly are unavailable. It does not relax any invariant.

## 4. Apply hard rejection tests

Run these tests in order. Stop at the first failure and rebuild the current stage from the construction contract.

### Blank-silhouette test

Mentally remove interior divisions. If recognition still depends mainly on a detailed fur edge, petal edge, leaflet edge, roof-tile edge, bracket contour, or other photographic silhouette, the result is contour translation. Reject it.

### Primitive-removal test

Mentally remove the obvious circles, ellipses, rectangles, polygons, and arcs. If a detailed freehand outline still carries most of the image, the primitives are decorative rather than structural. Reject it.

### Ten-percent thumbnail test

View the panel at about 10% of final width. The planned primary masses and dominant direction must read before texture or repeated detail. If individual hairs, leaves, tiles, brackets, flowers, stones, or background objects dominate, reject it.

### Budget test

Count visible major structures, representative repeated modules, background regions, and background axes. If the artifact materially exceeds the contract without an identity-based justification, reject it rather than rewriting the budget after generation.

### Transformation test

Overlay or rapidly alternate the middle and bottom panels when possible. Outer contours, internal divisions, overlaps, modules, and negative spaces must coincide. Any shifted, added, removed, merged, split, scaled, or redrawn shape fails.

### Source-preservation test

Compare the top panel with the input. Aside from proportional scale and an approved safe crop or fit, any relighting, retouching, reconstruction, extension, perspective change, or altered content fails.

## 5. Batch behavior

Process each image as an independent gated item. Parallel planning is acceptable, but do not approve or deliver the batch until every image passes its own master, color, registration, integrity, and source-preservation gates.

Do not continue from a failed geometric master merely to save generation time. Do not let completion of other images lower the acceptance threshold. Save rejected attempts separately only when useful for diagnosis; never present them as final results.

Use a bounded retry policy: make up to two focused rebuilds after the first failed attempt. Each retry must change the construction contract or prompt at the first failed gate rather than append more negative wording. If the same gate still fails after three total attempts, report the limitation and the failed invariant instead of silently accepting the result.
