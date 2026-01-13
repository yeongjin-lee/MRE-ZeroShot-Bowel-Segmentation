# Abstract

Crohn’s disease is a chronic inflammatory bowel disease with frequent relapse, making accurate bowel segmentation in Magnetic Resonance Enterography (MRE) essential for identifying the location and extent of lesions.  
This study proposes and evaluates a zero-shot bowel segmentation approach that directly applies a foundation model to MRE images without additional fine-tuning based on manual annotations.

We applied the publicly pre-trained MRSegmentator model to MRE data from 208 patients with Crohn’s disease to segment the small and large bowel regions without any task-specific training.  
Despite the zero-shot setting, the proposed method achieved a mean Dice similarity coefficient of 69.5%, demonstrating the feasibility and potential utility of zero-shot bowel segmentation in MRE.
