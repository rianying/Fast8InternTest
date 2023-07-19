# Fast8 Data Analyst Internship Test

This repository contains the analysis and findings for the Fast8 Data Analyst Internship Test. The analysis was conducted using Python and the dataset provided.

## Dataset Preparation

Before diving into the analysis using Python, several steps were taken to clean and preprocess the dataset. These steps were performed using Google Sheets and included:

- Transforming the 'Jumlah Karyawan' column by removing non-numeric characters and consolidating it into a new column named 'JumlahKaryawan'.
- Cleaning the 'Tingkat keluar masuk karyawan' column by removing additional descriptions within parentheses, leaving only the category names.
- Extracting the time values from the 'Jadwal kerja macam apa saja yang ada di tempat usaha Anda?' column and creating two new columns: 'JamMasuk' and 'JamKeluar'.
- Grouping values in the 'Jika menggunakan sistem HRD, sebutkan nama sistem HRD yang Anda gunakan' column to ensure consistency.
- Grouping values in the 'Apakah THR di perusahaan Anda dibagikan serentak atau berdasarkan agama yang dianut karyawan?' column into two categories: 'Serentak' and 'Agama'.
- Transforming the 'Berapa jumlah hari cuti yang diberikan setiap tahun?' column by removing non-numeric characters and consolidating it into a new column named 'JumlahHariCutiPertahun'.
- Renaming columns for better readability.
- Removing whitespace characters from the data.

These initial steps helped clean and prepare the raw data for further analysis using Python.

## Data Analysis

The data analysis was performed using Python with the help of various libraries, including pandas and matplotlib. The analysis focused on answering specific questions and generating insights from the dataset.

### Exploratory Data Analysis (EDA) Questions

1. Is there a relationship between 'TurnOver' (company turnover) and 'StatusKaryawan' (employee status)? How does the turnover vary for different employee statuses?
2. How does the 'CaraAbsensi' (attendance method) vary across different 'Provinsi' (provinces)? Are there any regional preferences or patterns in attendance tracking methods?
3. Is there a correlation between 'JumlahKaryawan' (number of employees) and 'BidangUsaha' (business sector)? Do certain business sectors tend to have larger or smaller employee counts?
4. Do companies that apply 'FasilitasBPJS' (BPJS facilities) also tend to provide 'ApakahCutiBersamaMemotongCutiTahunan' (deduct annual leave for collective holidays)? Is there any relationship between these two HR practices?
5. How does the 'KomponenPenggajianBerbeda' (different salary components) vary based on the 'StatusKaryawan' (employee status)? Are there specific salary components that are more commonly provided for certain employee statuses?

### Findings

The analysis provided the following insights:

- There is no concerning relationship between company turnover and employee status. The turnover rate was relatively consistent across different employee types.
- The majority of companies use a fingerprint attendance method, but a manual attendance method is still in use in some cases.
- Certain business sectors tend to have larger or smaller employee counts. The top 10 sectors with the most employees are primarily labor-intensive industries.
- Most companies that provide BPJS facilities deduct annual leave for collective holidays, but approximately 30% of companies do not deduct leaves.
- Salary components vary based on employee status, with specific components more commonly provided for certain statuses. Different employee statuses have different compensation structures.
- The top 5 most common business sectors among the dataset are identified.
- The top 5 provinces and cities with the highest number of companies are identified.
- The distribution of turnover values among companies shows that most companies have a low turnover rate.
- The most common employee status among the companies is identified.

Please refer to the original article for a detailed explanation of the analysis steps, code snippets, and visualizations.

Happy analyzing!

## Author

`Rahmadiyan Muhammad`

- Medium: [https://medium.com/@rianying
- Linkedin: [https://www.linkedin.com/in/rahmadiyanmuhammad/
