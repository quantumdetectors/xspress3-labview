# xspress3-labview
LabView EPICS bindings for Xspress3
Developed by Sekizawa-san at Spring8


These prgrams are incleded in 'CA_lab'
* CaLabGet_Main.vi
* CaLabPut_Main.vi
* Get_PV.vi
* Put_DBL_PV.vi
* Put_I16-1D_PV.vi
* Put_I32_PV.vi
* PV info.ctl


Sub VIs.
* XSP3_GetDBL(1D).vi
* XSP3_GetDBL.vi
* XSP3_GetString.vi
* XSP3_PutDBL.vi
* XSP3_PutI32.vi
* XSP3_PutString(1D).vi


Control programs for Xspress3.
* XSP3_ControlAcquire.vi
  Start/Stop acquision
* XSP3_ControlChannelVisualization.vi
  Enable/Disable ROI Visualization. Change 'enable' to get ROI data.
* XSP3_ControlDeadTimeCorrect.vi
  Enable/Disable dead time correction.
* XSP3_ControlEraseData.vi
  Clear data. 'ON' flag is not change to 'OFF' automatically. You need to send 'OFF' again.
* XSP3_ControlExtraROI.vi
  Enable/Disable extra ROIs(ROI5-16) (But this command is not working!)
* XSP3_ControlFileSave.vi
  Start/Stop file saving mode.
* XSP3_ControlROI.vi
  Enable/Disable ROI calculation.
* XSP3_ControlTrigger.vi
  Change trigger mode.
* XSP3_ControlUpdate.vi
  Update data. 'ON' flag is not change to 'OFF' automatically. You need to send 'OFF' again.
* XSP3_GetAcquireStatus.vi
  Get acuisition status.
* XSP3_GetFrame.vi
  Get total number of frames acquired.
* XSP3_GetIcr.vi
  Get all event scaler.
* XSP3_GetIcrArray.vi
  Get all event scaler array.
* XSP3_GetMca.vi
  Get MCA spectra data.
* XSP3_GetMcaSum.vi
  Get MCA spectra array data.
* XSP3_GetRoi.vi
  Get 1st ROI data.
* XSP3_GetRoiArray.vi
  Get ROI array data.
* XSP3_GetStatusMessage.vi
  Get status message.
* XSP3_SetAcquireTime.vi
  Set Acquisition time. (max. 50 s)
* XSP3_SetFileName.vi
  Set File name. (This program is not change file path)
* XSP3_SetFileNumber.vi
  Set File index number.
* XSP3_SetNumberOfImages.vi
  Set number of frames to acuire.
* XSP3_SetRoiHlm.vi
  Set higher limit of ROI.
* XSP3_SetRoiLlm.vi
  Set lower limit of ROI.


Sample programs.
* XSP3_Get_Data.vi
  Get ICR/MCA data program after acquisition with offset calcualtion.
* Xsprees3_Set_ROI.vi
  Set the ROI limit value and output the setting to txt file.
* Xspress3_Monitor.vi
  Live monitor program.
  Save the mca data to txt file, when push 'Save' button or reached to 'SaveExposureTime'.
