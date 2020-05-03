# DICOM-Preloader
A collection of Python scripts, that are intended to (pre)load DICOM studies. The idea is, to have a third party system sheduling those scripts and have them sending DICOM commands to the PACS/Modality/Postprocessing App to ensure that the required preliminary examinations are available on the right system at the right time.

The DICOM communication, mainly Query/Retrieve, Modality Worklist and C-MOVE operations, is facilitated by the pydicom/pynetdicom modules. See https://pydicom.github.io/ for more information.
