# Awesome Abdomen

> A curated list of anatomical features in the human abdomen and relevant open datasets.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Inspired by the [Awesome Manifesto](https://github.com/sindresorhus/awesome/blob/master/awesome.md), the goal is to create an **exhaustive** list of objects that could present in the human abdomen, along with all open datasets relevant to each object. See [awesome_anatomy.md](awesome_anatomy.md) for more information.

See something missing? Check out our [Contribution Guidelines](contributing.md) and fix it!

## Table of Contents

- [Awesome Abdomen](#awesome-abdomen)
  - [Table of Contents](#table-of-contents)
  - [Digestive Tract](#digestive-tract)
    - [Stomach](#stomach)
    - [Small Intestine](#small-intestine)
    - [Large Intestine](#large-intestine)
    - [Appendix](#appendix)
  - [Accesories to Digestive Tract](#accesories-to-digestive-tract)
    - [Liver](#liver)
    - [Gallbladder](#gallbladder)
    - [Pancreas](#pancreas)
  - [Urinary System](#urinary-system)
    - [Kidneys](#kidneys)
    - [Ureters](#ureters)
    - [Urinary Bladder](#urinary-bladder)
  - [Other Organs](#other-organs)
    - [Spleen](#spleen)
    - [Uterus](#uterus)
    - [Prostate](#prostate)
    - [Adrenal Glands](#adrenal-glands)
  - [Bones](#bones)
    - [Lumbar Vertebrae](#lumbar-vertebrae)
    - [Ribs](#ribs)
    - [Pelvis](#pelvis)
  - [Veins](#veins)
    - [Inferior Vena Cava](#inferior-vena-cava)
    - [Renal Veins](#renal-veins)
    - [Gonadal Veins](#gonadal-veins)
    - [Hepatic Veins](#hepatic-veins)
    - [Portal Vein](#portal-vein)
  - [Arteries](#arteries)
    - [Abdominal Descending Aorta](#abdominal-descending-aorta)
    - [Renal Arteries](#renal-arteries)
    - [Gonadal Arteries](#gonadal-arteries)
    - [Celiac Artery](#celiac-artery)
    - [Common Hepatic Artery](#common-hepatic-artery)
    - [Gastroduodenal Artery](#gastroduodenal-artery)
    - [Right Gastric Artery](#right-gastric-artery)
    - [Left Gastric Artery](#left-gastric-artery)
    - [Hepatic Artery Proper](#hepatic-artery-proper)
    - [Splenic Artery](#splenic-artery)
  - [Muscles](#muscles)
    - [Rectus Abdominis](#rectus-abdominis)
    - [Transverse Abdominal](#transverse-abdominal)
    - [Quadratus Lumborum](#quadratus-lumborum)
    - [External Oblique](#external-oblique)
    - [Internal Oblique](#internal-oblique)
  - [Fat](#fat)
    - [Subcutaneous](#subcutaneous)
    - [Extraperitoneal](#extraperitoneal)
  - [Membranes](#membranes)
    - [Skin](#skin)
    - [Peritoneum](#peritoneum)
    - [Omentum](#omentum)
    - [Masentry](#masentry)
    - [Outer Fascia](#outer-fascia)
    - [Inner Fascia](#inner-fascia)
    - [Falciform Ligament](#falciform-ligament)

## Digestive Tract

The Digestive Tract is an organ system which takes in food, extracts energy and nutrients, and expels the remaining waste as feces. [Wikipedia](https://en.wikipedia.org/wiki/Gastrointestinal_tract)

### Stomach

The stomach is located between the oesophegus and the small intestine. It secretes enzymes and acid to aid in digestion. [Wikipedia](https://en.wikipedia.org/wiki/Stomach)

**Conditions & Open Data**

- Healthy Controls
- Stomach Adenocarcinoma
  - [TCGA-STAD](https://wiki.cancerimagingarchive.net/display/Public/TCGA-STAD)
    - Radiology
      - CT
    - Pathology
      - WSI
    - Genomics ([separate url](https://portal.gdc.cancer.gov/projects/TCGA-STAD)) &#x1F535;
    - Clinical Data
- Lymphoma
- GIST
- Gastrointestinal Carcinoid Tumors
- Gastritis
- Gastroenteritis
- Gastroparesis
- Non-ulcer Dyspepsia
- Peptic Ulcers

### Small Intestine

Also known as the small bowel, the small intestine lies between the stomach and the large intestine, and it consists of three distinct regions: the duodenum, jejunum, and the ileum. The primary function of the small intestine is the absorbtion of nutrients and minearals from food. [Wikipedia](https://en.wikipedia.org/wiki/Small_intestine)

**Conditions & Open Data**

- Healthy Controls
- Celiac Disease
- Bowel Obstruction
- Inflamatory Bowel Disease
- Small Intestinal Bacterial Overgrowth

### Large Intestine

Also known as the large bowel, the large intestine is the final part of the GI tract. In the order in which waste material travels through, it consists of cecum, ascending colon, transverse colon, descending colon, sigmoid colon, rectum, and anal canal. It's primary purpose is absorbtion of water from waste material and storing feces. [Wikipedia](https://en.wikipedia.org/wiki/Large_intestine)

**Conditions & Open Data**

- Healthy Controls
- Inflammatory Bowel Disease

### Appendix

The appendix is a finger-like tube connected to the cecum at the junction of the small and large intestines. It is often considered to be a vestigial organ due to the lack of side effects upon its removal, but there is evidence to suggest that it supports the growth of useful intestinal bacteria. [Wikipedia](https://en.wikipedia.org/wiki/Appendix_(anatomy))

**Conditions & Open Data**

- Healthy Controls
- Appendicitis
- Fecalith
- Carcinoid Tumors
- Adenocarcinoid Tumors
- Goblet Cell Carcinomas
- Colonic-Type Adenocarcinoma
- Non-carcinoid Appendix Tumors
- Signet-Ring Cell Adenocarcinoma

## Accesories to Digestive Tract

These are organs which are not considered to be part of the digestive tract itself, but are nonetheless instrumental to digestion.

### Liver

The liver is located in the right upper abdomen below the diaphram. It produces biochemicals for digestion, regulates glycogen storage, red blood cell decomposition, and hormone production. [Wikipedia](https://en.wikipedia.org/wiki/Liver)

**Conditions & Open Data**

- Healthy Controls
  - [CHAOS Challenge Data](https://zenodo.org/record/3431873)
    - Radiology
      - CT, MR
    - Segmentations of Kidneys, Liver, and Spleen &#x1F537;
- Hepatocellular Carcinoma
  - [LiTS Challenge Data](https://competitions.codalab.org/competitions/17094)
    - Radiology
      - MR, CT + Segmentations &#x1F537;
  - [TCGA-LIHC](https://wiki.cancerimagingarchive.net/display/Public/TCGA-LIHC)
    - Radiology
      - MR, CT, PT
    - Pathology
      - WSI
    - Clinical Data
    - Genomics ([separate url](https://portal.gdc.cancer.gov/projects/TCGA-LIHC)) &#x1F535;
- Cholangiocarcinoma
- Angiosarcoma
- Hemoblastoma
- Hepatitis A
- Hepatitis B
- Hepatitis C
- Autoimmune Hepatitis
- Primary Biliary Cirrhosis
- Primary Sclerosing Cholangitis
- Hemochromatosis
- Hyperoxaluria
- Oxalosis
- Wilson's Disease
- Alpha-1 Antritrypsin Deficiency
- Chronic Alcohol Abuse
- Nonalcoholis Fatty Liver Disease

### Gallbladder

The gallbladder is a small organ which lies beneath the liver. It receives and stores bile from the liver, and rleases it into the duodenum where it helps in the digestion of fats. [Wikipedia](https://en.wikipedia.org/wiki/Gallbladder)

**Conditions & Open Data**

- Healthy Controls
- Gallbladder Cancer
- Gallstones
- Cholecystitis
- Choledocholithiasis
- Acalculous Gallbladder Disease
- Biliary Dyskinesia
- Sclerosing Cholangitis
- Gallbladder Polyps
- Gangrene of the Gallbladder
- Abscess of the Gallbladder

### Pancreas

The pancreas is located in the abdominal cavity behind the stomach. It secretes
several hormones into blood including insulin, as well as pancreatic juice into
the duodenum. [Wikipedia](https://en.wikipedia.org/wiki/Pancreas)

**Conditions & Open Data**

- Healthy Controls
  - [NIH Clinical Center Pancreas-CT](https://wiki.cancerimagingarchive.net/display/Public/Pancreas-CT)
    - Radiology
      - CT + Segmentations &#x1F537;
- Ductal Adenocarcinoma
  - [CPTAC-PDA](https://wiki.cancerimagingarchive.net/display/Public/CPTAC-PDA)
    - Radiology
      - CT, MR, DX, CR
    - Pathology
      - WSI
    - Proteomics
    - Clinical Data
- Neoendocrine Tumor
- Intraductal Papillary Mucinous Neoplasm
- Pancreatitis
- Type 1 Diabetes
- Hypertriglyceridemia
- Pancreatic Cyst
- Cystic Fibrosis

## Urinary System

The urinary system serves several purposes, including the elimination of waste, the regulation of blood volume and pressure, the regulation of levels of electrolytes adn metabolites, and the regulation of blood pH. [Wikipedia](https://en.wikipedia.org/wiki/Urinary_system)

### Kidneys

The kidneys are two bean-shaped organs located on the left and right in the retroperitoneal space. Kidneys' primary function is filtration of blood plasma, but they are also responsible for the synthesis of certain hormones and the conversion of vitamin D to calcitriol. [Wikipedia](https://en.wikipedia.org/wiki/Kidney)

**Conditions & Open Data**

- Healthy Controls
  - [CHAOS Challenge Data](https://zenodo.org/record/3431873)
    - Radiology
      - CT, MR
    - Segmentations of Kidneys, Liver, and Spleen &#x1F537;
- Renal Tumors (Various Types)
  - [KiTS19](https://github.com/neheller/kits19)
    - Radiology
      - CT
    - Segmentations of Kidneys and Kidney Tumors &#x1F537;
- Renal Clear Cell Carcinoma
  - [CPTAC-CCRCC](https://wiki.cancerimagingarchive.net/display/Public/CPTAC-CCRCC)
    - Radiology
      - CT, MR
    - Pathology
      - WSI
    - Proteomics
  - [TCGA-KIRC](http://dx.doi.org/10.7937/K9/TCIA.2016.V6PBVTDR)
    - Radiology
      - CT, MR, CR
    - Pathology
      - WSI
    - Genomics ([separate url](https://portal.gdc.cancer.gov/projects/TCGA-KIRC)) &#x1F535;
- Renal Papillary Carcinoma
  - [TCGA-KIRP](http://dx.doi.org/10.7937/K9/TCIA.2016.ACWOGBEF)
    - Radiology
      - CT, MR, PT
    - Pathology
      - WSI
    - Genomics ([separate url](https://portal.gdc.cancer.gov/projects/TCGA-KIRP)) &#x1F535;
- Renal Chromophobe Carcinoma
  - [TCGA-KICH](http://dx.doi.org/10.7937/K9/TCIA.2016.YU3RBCZN)
    - Radiology
      - CT, MR
    - Pathology
    - Genomics ([separate url](https://portal.gdc.cancer.gov/projects/TCGA-KICH)) &#x1F535;
- Transitional Cell Carcinoma
- Sarcoma
- Wilms Tumor
- Lymphoma
- Renal Cyst
- Cystic Kidney Disease
- Polycystic Kidney Disease
- Automsomal Dominant Polycystic Kidney Disease
- Autosomal Recessive Polycystic Kidney Disease
- Multicystic Dysplastic Kidney
- Nephritis
- Pyelonephritis
- Interstitial Nephritis
- Glomerulonephritis
- Lupus Nephritis
- Diabetic Nephropathy
- IgA Nephropathy
- Hematuria
- Uremia
- Neprotic Syndrom
- Goodpasture Syndrome
- Alport Syndrome
- Amyloidosis
- Atherosclerosis
- Renal Tubular Acidosis
- Focal Segmental Glomerulosclerosis
- Renal Artery Stenosis
- Chronic Kidney Disease
- Henoch-Schonlein Pupura
- Medullary Sponge Kidney
- Vesicoureteral Reflux
- Urinary Tract Obstruction
- Urinary Tract Infection
- Acute Kidney Injury
- Kidney Stone

### Ureters

The ureters are tubes that run from the kidneys to the urinary bladder. Their purpose is to carry fluid extracted by the kidneys to the bladder for excretion. [Wikipedia](https://en.wikipedia.org/wiki/Ureter)

**Conditions & Open Data**

- Healthy Controls
- Urinary Tract Obstruction
- Vesicoureteral Reflux
- Hydronephrosis
- Kidney Stones
- Ureterocele
- Calculus
- Retroperitoneal Fibrosis
- Duplicated Ureter
- Ectopic Ureter
- Transitional Cell Carcinoma (see [Kidneys](#kidneys))
- Megaureter
- Bladder Outlet Obstruction
- Renal Colic
- Ureteritis

### Urinary Bladder

The urinary bladder, often simply called bladder, is a distensible organ that sits on the pelvic floor. It's purpose is to store urine from the ureters until it exits through the urethra. [Wikipedia](https://en.wikipedia.org/wiki/Urinary_bladder)

**Conditions & Open Data**

- Healthy Controls
- Urothelial Carcinoma
  - [TCGA-BLCA](https://wiki.cancerimagingarchive.net/display/Public/TCGA-BLCA)
    - Radiology
      - CT, CR, MR, PT
    - Pathology
      - WSI
    - Genomics ([separate url](https://portal.gdc.cancer.gov/projects/TCGA-BLCA)) &#x1F535;
    - Clinical Information
- Squamous Cell Carcinoma
- Adenocarcinoma
- Urinary Tract Infection
- Interstitial Cystitis
- Overactive Bladder
- Cystocele
- Urinary Incontinence
- Hematuria
- Urinary Retention
- Neurogenic Bladder Dysfunction
- Stones
- Benign Prostatic Hyperplasia
- Pyelonephritis
- Vesiocoureteral Reflux
- Stress Incontinence
- Nocturia
- Nocturnal Enuresis
- Hunner's Ulcer
- Bladder Exstrophy
- Prolapse
- Urethritis
- Hydronephrosis

## Other Organs

Organs which don't fit nicely into any of the other categories. Ideas for better organizing this data [are welcome](https://github.com/neheller/awesome-abdomen/issues).

### Spleen

The spleen is a purple organ in the left upper quadrant of the abdomen, and it plays important roles with regard to red blood cells, and the immune system. It removes old red blood cells, holds a reserve of them, and recycles iron, and its immune function is to metabolize hemoglobin. [Wikipedia](https://en.wikipedia.org/wiki/Spleen)

**Conditions & Open Data**

- Healthy Controls
  - [CHAOS Challenge Data](https://zenodo.org/record/3431873)
    - Radiology
      - CT, MR
    - Segmentations of Kidneys, Liver, and Spleen &#x1F537;
- Lymphoma
- Leukemia
- Splenomegaly
- Splenic Injury
- Gaucher's Disease
- Infectious Mononucleosis
- Hemolytic Anemia
- Hereditary Spherocytosis
- Asplenia
- Spenic Infarction
- Portal Hypertension
- Myelofibrosis
- Accessory Spleen
- Wandering Spleen
- Infantile Hemangioma
- Extramedullary Hematopoiesis

### Uterus

Also known as the womb, the uterus is an organ of the female reproductive system. The superior end (the fundus) is connected to the fallopian tubes while the inferior end (the cervix) opens to the vagina. [Wikipedia](https://en.wikipedia.org/wiki/Uterus)

**Conditions & Open Data**

- Healthy Controls
- Uterine Sarcoma
- Endometrial Carcinoma
  - [CPTAC-UCEC](http://doi.org/10.7937/K9/TCIA.2018.3R3JUISW)
    - Radiology
      - CT, MR, PT, CR
    - Pathology
      - WSI
  - [TCGA-UCEC](http://dx.doi.org/10.7937/K9/TCIA.2016.GKJ0ZWAC)
    - Radiology
      - CT, CR, MR, PT
    - Pathology
      - WSI
    - Clinical Information
    - Genomics ([separate url](https://portal.gdc.cancer.gov/projects/TCGA-UCEC)) &#x1F535;
  - Adenocarcinoma
  - Carcinosarcoma
  - Squamous Cell Carcinoma
  - Undifferentiated Carcinoma
  - Small Cell Carcinoma
  - Transitional Carcinoma
- Uterine Fibroid
- Endometrial Polyp
- Cervical Cancer
- Ednometriosis
- Endometritis
- Menorrhagia
- Adenomyosis
- Endometrial Hyperplasia
- Ectopic Pregnancy
- Dysmenorrhea
- Metritits
- Pyometra
- Prolapse
- Leiomyoma
- Asherman's Syndrome
- Cercivitis
- Adhesion
- Retained Placenta
- Pelvic Organ Prolapse
- Obstructed Labor
- Uterus Didelphys
- Ovarian Cyst
- Uterine Rupture
- Uterine Malformation
- Fibroma
- Stenosis of Uterine Cervix
- Retroverted Uterus
- Postpartum Bleeding
- Hematometra
- Bicornuate Uterus
- Unicornuate Uterus

### Prostate

The prostate is a exocrine gland of the male reproductive system which sits between the bladder and the penis. The purpose of the prostate is to secrete an alkaline fluid constituting roughly 30% of the volume of semen, helping to neutralize the acidity of the vaginal tract. [Wikipedia](https://en.wikipedia.org/wiki/Prostate)

**Conditions & Open Data**

- Healthy Controls
- Prostate Cancer
  - [PROSTATEx Challenge](https://wiki.cancerimagingarchive.net/display/Public/SPIE-AAPM-NCI+PROSTATEx+Challenges#83450a9eb4144751b38cb85f7abcb711)
    - Radiology
      - MR
    - Lesion Locations
    - Clinical Information
  - [Prostate-Fused-MRI-Pathology](https://wiki.cancerimagingarchive.net/display/Public/Prostate+Fused-MRI-Pathology)
    - Radiology
      - MR
    - Pathology
      - WSI + Segmentations &#x1F537;
  - [QIN-Prostate-Repeatability](https://wiki.cancerimagingarchive.net/display/Public/QIN-PROSTATE-Repeatability)
    - Longitudinal (test-retest study with ~2 week interval)
    - Radiology
      - MR: T2w, DWI, DCE, ADC
    - Segmentations of prostate gland, peripheral zone, and lesion and normal tissue regions based on radiological appearance &#x1F537;
  - Adenocarcinoma
    - [TCGA-PRAD](https://wiki.cancerimagingarchive.net/display/Public/TCGA-PRAD#46af39dce8ee4f3eafa3f5305d907abc)
      - Radiology
        - CT, PT, MR
      - Pathology
      - Clinical Data
      - Genomics ([separate url](https://portal.gdc.cancer.gov/projects/TCGA-PRAD)) &#x1F535;
    - Acinar Adenocarcinoma
    - Ductal Adenocarcinoma
- Transitional Cell
- Squamous Cell
- Small Cell
- Benign Prostatic Hyperplasia
- Chronic Prostatitis
- Acute Prostatitis
- Hematuria
- Bladder Outlet Obstruction

### Adrenal Glands

The adrenal glands are endocrine glands that lie superior to the kidneys, hence they are sometimes called the "suprarenal glands". They produce a variety of hormones such as adrenaline, and steroids such as aldosterone and cortisol. [Wikipedia](https://en.wikipedia.org/wiki/Adrenal_gland)

**Conditions & Open Data**

- Healthy Controls
- Adrenal Tumor
  - Adrenocortical Carcinoma
  - Pheochromocytoma
- Cushing's Syndrome
- Adrenal Crisis
- Primary Aldosteronism
- Congenital Adrenal Hyperplasia
- Adrenal Inusfficiency
- Adrenoleukodystrophy
- Addison's Disease
- Hyperaldosteronism

## Bones

Bones are rigid organs which constitue the skeleton. The purpose of bones is to support and protect other organs, produce red and white blood cells, store minerals, and enable mobility. [Wikipedia](https://en.wikipedia.org/wiki/Bone)

### Lumbar Vertebrae

The lumbar vertebrae are the five vertebrae between the rib cage and pelvis. They help to support the weight of the body and permit movement. [Wikipedia](https://en.wikipedia.org/wiki/Lumbar_vertebrae)

**Conditions & Open Data**

- Healthy Controls
- Spinal Tumor
- Degenerative Disc Disease
- Splan Disc Herniation
- Spondylolisthesis
- Spondylosis
- Spondylolysis
- Spondylitis
- Spinal Fracture
  - Vertical Compression Fracture
- Lumbar Disc Disease
- Lumbar Spinal Stenosis
- Disc protrusion

### Ribs

Ribs are long curved bones which form the rib cage surrounding the chest. They serve to protect the internal organs of the thorax while allowing the lungs to expand during respiration. [Wikipedia](https://en.wikipedia.org/wiki/Rib)

**Conditions & Open Data**

- Healthy Controls
- Pancoast Tumor
- Rib Fracture
- Tietze Syndrome
- Fibrous Dysplasia of Bone
- Hypoplasia
- Flail Chest
- Preiosteal Reaction
- Pectus Excavatum
- Thoracic Outlet Syndrome
- Cervical Rib
- Asphyxiating Thoracic Dysplasia
- Short Rib
- Bifid Rib
- Pulmonary Contusion
- Microtia
- Spondylocostal Dysostosis

### Pelvis

The pelvis is the skeletal structure in the lower part of the human body between the abdomen and thighs. The pelvis serves as a connection between the spine and the lower limbs, and it creates a cavity mainly for reproductive organs. [Wikipedia](https://en.wikipedia.org/wiki/Pelvis)

**Conditions & Open Data**

- Healthy Controls
- Pelvic Fractures
- Osteitis Pubis
- Metastatic Bone Disease of the Pelvis
- Vanishing Bone Disease Involving the Pelvis

## Veins

Veins are blood vessels that carry blood toward the heart. Most veins carry deoxygenated blood from the tissues back to the heart, but some veins including pulmonary and umbilical veins carry oxygenated blood. [Wikipedia](https://en.wikipedia.org/wiki/Vein)

### Inferior Vena Cava

The Inferior Vena Cava (IVC) is a large vein which carries deoxygenated blood from the lower and middle body back to the heart. In the direction of flow, it begins where the left and right iliac veins join, and ends where it enters the right atrium of the heart. [Wikipedia](https://en.wikipedia.org/wiki/Inferior_vena_cava)

**Conditions & Open Data**

- Healthy Controls
- Leimyosarcoma of the IVC
- Double Inferior Vena Cava
- Inferior Vena Cava Syndrome

### Renal Veins

The Renal Veins are the veins that carry filtered blood away from the kidney to the inferior vena cava. [Wikipedia](https://en.wikipedia.org/wiki/Renal_vein)

**Conditions & Open Data**

- Healthy Controls
- Renal Vein Thrombosis
- Renal Nutcracker Syndrome

### Gonadal Veins

The gonadal veins are the blood vessels that carrie blood away from the testis (male) or ovaries (female) to the inferior vena cava. [Wikipedia](https://en.wikipedia.org/wiki/Gonadal_vein)

**Conditions & Open Data**

- Healthy Controls
- Pelvic Vein Disease
- Pelvic Venous Congestion Syndrome
- Ovarian Vein Syndrome
- Female Gonadal Vein Insufficiency
- Gonadal Vein Thrombosis

### Hepatic Veins

The hepatic veins are the blood vessels that carrie blood away from the liver and into the inferior vena cava. There are usually three hepatic veins draining from the left, middle, and right parts of the liver. [Wikipedia](https://en.wikipedia.org/wiki/Hepatic_veins)

**Conditions & Open Data**

- Healthy Controls
- Budd-Chiari Syndrome
- Hepatic Veno-occlusive Disease

### Portal Vein

Also known as the hepatic portal vein, the portal vein is a blood vessel that carries blood with nutrients and toxins from the GI tract, gallbladder, pancreas, and spleen to the liver. The portal vein accounts for roughly 75% of liver blood flow. [Wikipedia](https://en.wikipedia.org/wiki/Portal_vein)

**Conditions & Open Data**

- Healthy Controls
- Portal Venous Gas
- Portosystemic Shunt
- Portal Hypertension
- Portal Vein Thrombosis
- Pylephlebitis
- Gastric Varices
- Non-cirrhotic Portal Fibrosis

## Arteries

Arteries are blood vessels that take blood away from the heart. Most arteries carry oxygenated blood, with the exception of the pulmonary and umbilical arteries. [Wikipedia](https://en.wikipedia.org/wiki/Artery)

### Abdominal Descending Aorta

The descending aorta is the largest artery in the body, running from the heart down to where it splits into the two common iliac arteries. It's purpose is to carry oxygenated blood to tissue in the middle and lower parts of the body. There is a large thoracic component to the descending aorta, but here we concern ourselves with only the abdominal component. [Wikipedia](https://en.wikipedia.org/wiki/Descending_aorta)

**Conditions & Open Data**

- Healthy Controls
- Abdominal Aortic Dissection
- Abdominal Aortic Aneurysm
- Abdominal Aortic Atherosclerosis

### Renal Arteries

The renal arteries are blood vessel arising from the left interior of the abdominal aorta and ending where they branch into capillaries in the renal hilum. These arteries carry as much as a third of all cardiac output through the kidneys for filtration. [Wikipedia](https://en.wikipedia.org/wiki/Renal_artery)

**Conditions & Open Data**

- Healthy Controls
- Renal Artery Stenosis
- Bruit
- Renal Artery Cholesterol Embolism
- Renovascular Hypertension
- Renal Artery Vasculaitis
- Fibromuscular Dysplasia
- Renal Artery Dissection

### Gonadal Arteries

The gonadal arteries arise from the abdominal aorta and end at each testical (male) or ovary (female). Their purpose is to supply oxygenated blood to the gonads. [Wikipedia](https://en.wikipedia.org/wiki/Gonadal_artery)

**Conditions & Open Data**

- Healthy Controls
- Gonadal Artery Aneurysm
-

### Celiac Artery

Also known as the celiac trunk, the celiac artery is the first major branch of the abdominal aorta around thoracic vertebrae 12. It terminates where it splits into the left gastric artery, the common hepatic artery, and the splenic artery. [Wikipedia](https://en.wikipedia.org/wiki/Celiac_artery)

**Conditions & Open Data**

- Healthy Controls
- Celiac Artery Dissection
- Celiac Artery Aneurysm
- Celiac Artery Stenosis

### Common Hepatic Artery

The common hepatic artery is a blood vessel that supplies oxygenated blood to the liver, pylorus of the stomach, duodenum, pancreas, and gallbladder. It arises from the celiac artery and branches into the hepatic artery proper, the gastroduodenal artery, and the right gastric artery. [Wikipedia](https://en.wikipedia.org/wiki/Common_hepatic_artery)

**Conditions & Open Data**

- Healthy Controls

### Gastroduodenal Artery

The gastroduodenal artery is a small blood vessel in the abdomen that supplies blood directly to the pylorus and duodenum, and indirectly to the pancreatic head. It typically arises from the common hepatic artery and terminates when it splits into the right gastroepiploic arter and the anterior superior pancreaticoduodenal artery. [Wikipedia](https://en.wikipedia.org/wiki/Gastroduodenal_artery)

**Conditions & Open Data**

- Healthy Controls
- Peptic Ulcer Disease
- Gastroduodenal Artery Aneurysm
- Gastroduodenal Artery Dissection

### Right Gastric Artery

The right gastric artery arises from the common hepatic artery and supplies oxygenated blood to the pyloric end of the stomach along its lesser curvature, until it terminates by anastamosing with the left gastric artery. [Wikipedia](https://en.wikipedia.org/wiki/Right_gastric_artery)

**Conditions & Open Data**

- Healthy Controls
- Right Gastric Artery Aneurysm
- Right Gastric Artery Dissection

### Left Gastric Artery

The left gastric artery arises from the celiac artery and supplies oxygenated blood to the stomach along the superior portion of its lesser curvature, until it terminates by anastamosing with the right gastric artery. [Wikipedia](https://en.wikipedia.org/wiki/Left_gastric_artery)

**Conditions & Open Data**

- Healthy Controls
- Left Gastric Artery Aneurysm
- Left Gastric Artery Dissection

### Hepatic Artery Proper

Also called the proper hepatic artery, the hepatic artery proper arises from the common hepatic artery and supplies the liver and gallbladder. [Wikipedia](https://en.wikipedia.org/wiki/Hepatic_artery_proper)

**Conditions & Open Data**

- Healthy Controls
- Hepatic Artery Proper Stenosis
- Hepatic Artery Proper Aneurysm
- Hepatic Artery Proper Dissection

### Splenic Artery

The splenic artery (formerly called the lienal artery) supplies oxygenated blood to the spleen. It arises from the celiac artery and runs superior to the pancreas. [Wikipedia](https://en.wikipedia.org/wiki/Splenic_artery)

**Conditions & Open Data**

- Healthy Controls
- Splenic Artery Aneurysm
- Splenic Artery Pseudoaneurysm
- Splenic Artery Dissection
- Splenic Artery Stenosis

## Muscles

### Rectus Abdominis

TODO

**Conditions & Open Data**

- Healthy Controls

### Transverse Abdominal

TODO

**Conditions & Open Data**

- Healthy Controls

### Quadratus Lumborum

TODO

**Conditions & Open Data**

- Healthy Controls

### External Oblique

TODO

**Conditions & Open Data**

- Healthy Controls

### Internal Oblique

TODO

**Conditions & Open Data**

- Healthy Controls

## Fat

### Subcutaneous

TODO

**Conditions & Open Data**

- Healthy Controls

### Extraperitoneal

TODO

**Conditions & Open Data**

- Healthy Controls

## Membranes

### Skin

TODO

**Conditions & Open Data**

- Healthy Controls

### Peritoneum

TODO

**Conditions & Open Data**

- Healthy Controls

### Omentum

TODO

**Conditions & Open Data**

- Healthy Controls

### Masentry

TODO

**Conditions & Open Data**

- Healthy Controls

### Outer Fascia

TODO

**Conditions & Open Data**

- Healthy Controls

### Inner Fascia

TODO

**Conditions & Open Data**

- Healthy Controls

### Falciform Ligament

TODO

**Conditions & Open Data**

- Healthy Controls
