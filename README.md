# medical-data
This repo is meant to be used as some sort of cheat sheet for working with medical data plus medical image processing.

There are two common formats that medical images (X-Ray, CT, MRI, PET) are stored in:

- DICOM (used in clinial settings)
  
    has a *header* and a *body*:
  
      - Header: contains additional information about the patient, medical imaging device, ...
      - Body: contains actual image pixel data
  
- NIFTI (used in research settings)
