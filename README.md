# CRFs_4_GeneIdentification
Repository that storages the data, scripts and results from the project carried out by Carlos Ángel and Vicente Fajardo with the goal to apply CRFs to gene name identification in the biomedical literature.
El directorio root dirige al directorio principal, conditional-random-fields, el cual contiene todos los datos. En este, son de interés los siguientes archivos/directiorios:
	training-validation-original.py	Script de entrenamiento y evaluación del método de CRFs original (proporcionado, véanse parámetros).
	training-validation-v1-more_func.py	Script modificado con las nuevas funciones (véanse parámetros).
	combinations.py	Programa para generar las distintas combinatorias.
	run_combinations_crf.bash	Bash para correr las combinatorias generadas por todas las funciones.
	run_10_best_comb_general_200abs.bash	Correr con distintos tamaños de corpus para las 10 mejores combinatorias.
	run_10_best_comb_general_300abs.bash
	run_10_best_comb_general_completeabs.bash
	models	Directorio para guardar los modelos generados por el script de entrenamiento/evaluación.
	data-sets	Directorio para almacenar los conjuntos de datos de entrenamiento y evaluación (distintos tamaños).
	reports	Directorio para almacenar los reportes de los diversos procesos de entrenamiento y evaluación.
