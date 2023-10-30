1. buka aplikasi PSQL untuk membuat tugas yang akan di kerjakan
![Screenshot (306)](https://github.com/DewiYuliaPuspitasari/pertemuan2_BasisData/assets/148309663/2bfe6c65-9752-41f0-82ab-d2fd0cbcf742)
2. kemudian muncul tampilan seperti dibawah 
![image](https://github.com/DewiYuliaPuspitasari/pertemuan2_BasisData/assets/148309663/77f84b83-de91-4ff3-ac81-4abee3dc3113)
![image](https://github.com/DewiYuliaPuspitasari/pertemuan2_BasisData/assets/148309663/92d0be75-912c-4bde-b3c4-19d2fb70fe2c)
3. membuat tabel Mahasiswa
- masukan kedalam database dengan syntax = \c polban
 ![image](https://github.com/DewiYuliaPuspitasari/pertemuan2_BasisData/assets/148309663/0cc97a66-33a9-47a4-b47c-fc6da133922e)
- membuat data dengan memasukan data (L/P) dengan syntax =  create type gender AS ENUM ('L', 'P');
![image](https://github.com/DewiYuliaPuspitasari/pertemuan2_BasisData/assets/148309663/b7d4fc7e-6373-4fa4-9246-cbfe1777fed8)
- membuat tabel dengan syntax = create table Mahasiswa (column1 datatype(length) columnt_constrait, columnN datatype(length) column_constrait);
![image](https://github.com/DewiYuliaPuspitasari/pertemuan2_BasisData/assets/148309663/18b81664-55b5-4461-862f-5bd008119577)
- cek data table dengan syntax = \dt
![image](https://github.com/DewiYuliaPuspitasari/pertemuan2_BasisData/assets/148309663/37b4282b-d4b0-4812-be4e-8756ab7d9234)
- buat data database yang akan dibuat dengan syntax = insert into Mahasiswa (column1, columnN) VALUES (value1, valueN);
![image](https://github.com/DewiYuliaPuspitasari/pertemuan2_BasisData/assets/148309663/d977123d-3b47-42ed-9ad6-bac29dde24d0)
