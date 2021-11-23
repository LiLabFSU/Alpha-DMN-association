fMRI Data:
Folders containing double contrasts (Active minus Sham - Post minus Pre) for each ROI = 'xxx_doubleT'
Single contrasts (Post minus Pre) for each ROI = 'xxx_pairT_active/sham'
Baseline connectivity for each ROI = 'xxx_oneT_pre'
Folder containing ROI masks = 'Masks'

EEG Data:
Power for all frequencies for all channels averaged across groups = 'active_sham_pre_post_EEG_power.mat'
	* f = frequencies
	* chanlocs = channel location file
GC for all frequencies for right/left hemisphere electrode pairs averaged across groups = 'active_sham_pre_post_EEG_GC.mat'
	* freq_range = frequencies