AI-GENERATED CITRUS LEAF DATASET FOR A CHILDREN'S WORKSHOP
Prepared: 10 October 2026

CLASSES AND COUNTS
Leaf_miner: 20 images. Synthetic depictions of citrus leaf-miner DAMAGE: pale winding mines beneath the leaf surface, often with a fine brown central trail and slight curling. These show the damage, not a photograph of an exposed adult insect.
Healthy_leaves: 20 images. Synthetic healthy-looking citrus foliage without visible mines, soot-like coating, major disease spots, or pests. The label describes appearance, not a diagnostic examination.
Sooty_Mold: 20 images. Synthetic depictions of an irregular superficial charcoal/gray-black soot-like coating on intact green citrus leaves. No fungal species or laboratory diagnosis is claimed.
Total: 60 JPEG images, balanced at exactly 20 per class. The three previously accepted sample images are included as 001.

WHY THESE CLASSES
The user's corrected classes are leaf-miner damage, healthy-looking citrus leaves, and sooty mold. They offer three approachable garden appearances: winding pale tunnels, apparently clean foliage, and a dark superficial coating. Keeping citrus-like leaves in every class reduces the chance that the model learns plant species instead of the intended condition. The examples connect AI classification with observation of garden leaves.

GENERATION AND QUALITY CONTROL
The user explicitly requested realistic AI-generated images after reviewing three trial samples. Every example was independently generated from a written prompt with the built-in image generation tool. Reference photographs and accepted samples guided subject appearance and natural everyday camera style. No source image was cropped, flipped, or recolored to create extra examples; no collage tiles were used as examples.
Prompts vary leaf shape, size, orientation, number of prominent leaves, damage/coating pattern, daylight, and garden backgrounds. All classes use overlapping background and lighting types. Every selected image was visually reviewed for its intended class, a recognizable target, natural photographic appearance, and obvious label conflicts or artifacts. Generated biology can still be imperfect.
All 60 original images were decoded. Exact file/pixel hashes and perceptual comparisons, including rotated and mirrored comparisons for duplicate detection only, covered all pairs across classes. Flagged pairs received visual review. Final files were converted once to JPEG quality 93, with aspect ratio preserved and longest edge at most 1440 pixels. Every delivered JPEG was fully decoded and verified. The CSV has one row per image.

PROVENANCE, ATTRIBUTION, AND REUSE
These are AI-generated synthetic pictures, not sourced photographs of real plants. There are no independent photographers or varied photographic source collections. The dataset deliberately follows the user's requested generated-image approach; it does not meet the original real-photo-only requirement.
The CSV source_url field is blank because these examples have no public photographic source page or direct image URL. source_name identifies the generator, and notes identify the user-supplied reference filenames and exact prompt entry. The original reference photographs are not included in the ZIP.
No Creative Commons license or public-domain status is claimed or assigned. OpenAI's Terms of Use state that, as between the user and OpenAI and to the extent permitted by applicable law, the user owns the output; they also require appropriate rights for input material and prohibit representing AI output as human-generated. Applicable terms and third-party rights still matter. The permissions of the user's reference images were not independently verified. Terms checked 10 October 2026: https://openai.com/policies/terms-of-use/
Suggested descriptive credit when displaying the examples: AI-generated citrus-leaf workshop images, created with OpenAI's image generation tool. Retain this README and CSV when sharing the dataset. This descriptive credit is provenance, not a newly imposed Creative Commons attribution condition.

LIMITATIONS
Class labels describe the intended generated visual condition; they are not independently verified biological ground truth. No real plant was examined, no insect species or fungal species was confirmed, and normal-looking foliage does not prove plant health. Visual realism cannot establish scientific accuracy.
All examples share a generator and reference style. A model may learn background, lighting, framing, leaf count, or generated presentation instead of the leaf condition. Matched variations reduce this risk but cannot eliminate it. No trained classifier was evaluated as part of preparing this ZIP. This small synthetic set supports a beginner demonstration; dependable real-world garden diagnosis is outside its scope.

TRAINING AND TESTING
Reserve at least 4 images per class for testing and do not upload those images during training. One suggested split is to reserve image numbers 003, 008, 013, and 018 in each class, leaving 16 for initial training. Keep the test labels separate until checking predictions.
Testing on held-out synthetic images measures performance only on this generated set. Also test with independently collected, correctly labeled real photographs that were not used as references or training images. Try new viewpoints and backgrounds and discuss mistakes with the children.

FILES
Each class folder contains 20 JPEGs. dataset_sources.csv records every image. generation_prompts.txt contains the exact prompts used. README.txt is this document.
