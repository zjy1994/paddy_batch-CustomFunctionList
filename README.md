# paddy_batch-CustomFunctionList
List of custom functions written in the file 'paddy_batch.ipynb' (Python Code in Jupyter Lab)

# 稻谷数据批量处理代码中的自定义函数列表

(1) calMag(Vi, VQ)

(2) calPhase(Vi, VQ)

(3) getData_txt(filepath)

(4) refData_singleThickness(path)

(5) refData_allThickness(path)

(6) expData_allThickness(path, path_Mag, path_Phase, save_csv=False, mc_folder='MC')

(7) expData_singleDay(path, path_Mag, path_Phase, save_csv=False, date_folder='2020')

(8) expData_allDay(path, path_Mag, path_Phase, date_list, save_csv=False)

(9) getData_csv(filepath)

(10) VNA_refData_singleThickness(path)

(11) VNA_refData_allThickness(path)

(12) VNA_expData_allThickness(path, path_Mag, path_Phase, path_expandPhase, save_csv=False, mc_folder='MC')

(13) VNA_expData_singleDay(path, path_Mag, path_Phase, path_expandPhase, save_csv=False, date_folder='2020')

(14) VNA_expData_allDay(path, path_Mag, path_Phase, path_expandPhase, date_list, save_csv=False)

(15) get_average_spectrum_from_OM2S2(path_A, path_mc, path_thickness, parent_path, save_csv=False, data_type='Attenuation')

(16) get_average_spectrum_from_VNA(path_A, path_mc, path_thickness, parent_path, save_csv=False)

(17) get_spectrum_data(path, mc_mark_list, parent_path, path_mc, thickness_list=['3cm'], save_csv=False, data_type='Attenuation', equipment='OM2S2')

