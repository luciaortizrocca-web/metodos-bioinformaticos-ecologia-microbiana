# Métodos Bioinformáticos en Ecología Microbiana

Curso teórico-práctico sobre procesamiento, análisis reproducible y ecología de comunidades microbianas a partir de datos de secuenciación masiva (NGS).

**Cátedra de Microbiología Agrícola**  
**Facultad de Agronomía — Universidad de Buenos Aires (FAUBA)**

---

### Docentes Responsables
**Marcelo Soria & Lucía Ortiz Rocca** — Cátedra de Microbiología Agrícola, FAUBA.

---

## 📌 Fundamentación y Objetivos

El análisis de comunidades microbianas mediante secuenciación de amplicones (*metabarcoding*) y metagenómica exige flujos de trabajo computacionales rigurosos, reproducibles y escalables. Este curso tiene como objetivo capacitar a estudiantes de grado y posgrado en el uso de la terminal de Linux, la automatización de análisis con gestores de flujo modernos y el procesamiento integral de secuencias del gen marcador 16S rRNA.

Al finalizar el curso, los y las estudiantes adquieren autonomía para:
1. Diseñar e interpretar pipelines reproducibles mediante **Snakemake**.
2. Evaluar críticamente la calidad de lecturas crudas (*Illumina*) y aplicar filtros de preprocesamiento (*FastQC, MultiQC, Cutadapt*).
3. Obtener variantes de secuencia de amplicones (**ASVs**) utilizando **DADA2 y QIIME 2**.
4. Realizar asignación taxonómica supervisada utilizando clasificadores *Naive Bayes* y bases de datos de referencia (**Greengenes**).
5. Cuantificar métricas de diversidad alfa y beta para contrastar hipótesis ecológicas en suelos, sedimentos y sistemas agrícolas.

---

## 🔬 Estructura del Programa Práctico

El programa se estructura en módulos progresivos orientados a la práctica bioinformática:

* **Módulo 0: Configuración de Entornos y Reproducibilidad**  
  Gestión de dependencias con Conda/Mamba. Instalación y resolución de incidencias en entornos dedicados para QIIME 2 (distribución Amplicon) y herramientas de control de calidad.

* **Módulo 1: Automatización con Snakemake**  
  Sintaxis y lógica declarativa en Snakemake. Reglas, entradas, salidas, comodines (`{wildcards}`), grafos dirigidos acíclicos (DAGs) y gestión de recursos.

* **Módulo 2: Control de Calidad y Preprocesamiento**  
  Inspección de calidad con FastQC y consolidación con MultiQC. Interpretación de perfiles Phred, remoción de secuencias de primers con Cutadapt y armado automatizado de archivos de manifiesto.

* **Módulo 3: Denoising y Generación de ASVs con QIIME 2**  
  Importación de lecturas pareadas, inspección interactiva (`.qzv`), corrección de errores y remoción de quimeras mediante DADA2 y QIIME 2. Comparación conceptual y analítica entre OTUs al 97% y ASVs.

* **Módulo 4: Taxonomía y Ecología de Comunidades**  
  Clasificación taxonómica Naive Bayes utilizando la base Greengenes. Filtrado de organelos (cloroplastos y mitocondrias). Métricas de diversidad alfa (riqueza, Chao1, Shannon) y beta (UniFrac, Bray-Curtis, PCoA).

---

## 💻 Entorno y Herramientas Utilizadas

* **Sistema Operativo:** GNU/Linux (Bash)
* **Gestión de Entornos:** Conda / Mamba
* **Pipeline Manager:** Snakemake
* **Análisis de Microbiomas:** QIIME 2 (Amplicon Release)
* **Algoritmo de Denoising:** DADA2
* **Control de Calidad:** FastQC, MultiQC, Cutadapt
* **Base de Referencia:** Greengenes

---

## 🔒 Solicitud de Material Didáctico

> ### 📢 Aviso sobre el acceso a guías y datasets
> Las guías prácticas de trabajos prácticos (TPs), los scripts de resolución y los conjuntos de datos asociados fueron desarrollados y curados íntegramente por los docentes de la materia.
>
> Con el propósito de **preservar la integridad pedagógica de las evaluaciones en cursadas activas** y garantizar el uso académico responsable, las guías completas no se encuentran publicadas de forma abierta en este repositorio.
>
> Docentes, investigadores y estudiantes que deseen consultar o utilizar este material con fines académicos pueden solicitar acceso a **ortizrocca@agro.uba.ar**.

---

## 📜 Propiedad Intelectual

© 2026-2027 **Marcelo Soria & Lucía Ortiz Rocca**.  
Cátedra de Microbiología Agrícola, Facultad de Agronomía, Universidad de Buenos Aires (FAUBA).  
*Todos los derechos reservados.*
