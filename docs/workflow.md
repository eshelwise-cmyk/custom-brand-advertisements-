# End-to-End Workflow

## 1. Context

Start with a brand intelligence file when one exists. Otherwise collect the minimum missing inputs: audience, offer, campaign goal, pains, desires, and visual constraints.

The output is a structured brand context record.

## 2. Scene mining

Create representative scenes from audience psychology. Use a mix of pain and desire situations when both are relevant.

The scene should communicate something about the audience, not merely display the product.

## 3. Style exploration

Hold the scene intent steady while exploring multiple visual directions. Random style-reference exploration is useful because it prevents the workflow from collapsing into the first familiar aesthetic.

The human selects finalists. The model does not decide the brand style by itself.

## 4. Style audition

Apply finalists to several different scenes. Test composition, emotional signal, audience relevance, and repeatability.

If a style only works on one image, it is not locked.

## 5. Style lock

Save the approved reference and parameters as a versioned style lock. Keep provider-specific settings in the provider adapter layer.

## 6. Ad generation

Generate concepts from the brand context and style lock. Every concept should have a clear audience trigger and a planned composition.

## 7. Layout

Reserve intentional negative space for copy, CTA, and brand marks. Generate the visual first and add final typography in the design layer when possible.

## 8. Batch

Expand approved scenes through controlled variations. The source workflow demonstrates grouped prompt variations for this purpose. Equivalent batching can be implemented directly for providers that do not support grouped syntax.

## 9. Quality control

Score outputs for brand consistency, audience relevance, distinctiveness, emotional clarity, composition, and production usability.

Delete or reject weak outputs. Do not let failed experiments contaminate the approved asset bank.

## 10. Asset bank

Store approved concepts with metadata linking them to the style-lock version and campaign. The bank becomes a reusable source for social posts, ads, landing pages, posters, and other brand communications.
