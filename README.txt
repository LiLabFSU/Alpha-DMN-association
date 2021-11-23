fMRI Data:
'xxx_doubleT' = Double contrasts (Active minus Sham - Post minus Pre) for each ROI 
'xxx_pairT_active/sham' = Single contrasts (Post minus Pre) for each ROI
'xxx_oneT_pre' = Baseline connectivity for each ROI
'Masks' = Folder containing ROI masks

EEG Data:
'active_sham_pre_post_EEG_power.mat' = Power for all frequencies for all channels averaged across groups
	* f = frequencies
	* chanlocs = channel location file
'active_sham_pre_post_EEG_GC.mat' = GC for all frequencies for right/left hemisphere electrode pairs averaged across groups 
	* freq_range = frequencies
