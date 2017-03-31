# Single Image Dehazing Using Color Ellipsoid Prior
By Trung Minh Bui, and Wonha Kim IEEE Senior Member 

College of Electronics and Information, 

Kyung Hee University, Kiheung, Kyunggi-do, Korea 

Email: minhtrung@khu.ac.kr, wonha@khu.ac.kr

# Introduction
Color Ellipsoid Prior (CEP) method is a dichromatic model-based dehazing
method that is statistically robust against image signal
randomness, performs effectively across a wide range of haze
degrees, does not require any post-refinement process, and
does not produce any apparently visible noise or halo artifacts.
Currently, it is one of the fastest image dehazing methods.

The CEP is described in T. M. Bui, and W. Kim, "Single Image Dehazing Using Color Ellipsoid Prior", submitted 
in IEEE transaction on Image processing, 2017.


# Download
[IMAGES] https://drive.google.com/file/d/0B6VA9ZgxISJcV0lQd2x3REdDejA/view?usp=sharing
# Dehazing results
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
# Input "Lake" image
![khu2](https://cloud.githubusercontent.com/assets/21355219/24392030/19d5f808-13cd-11e7-97d7-66108485967f.png)
# Dehazed by proposed CEP
![khu2_cep](https://cloud.githubusercontent.com/assets/21355219/24392033/19da1212-13cd-11e7-8bed-c95af7c952d0.png)
# Transmission by proposed CEP
![khu2_cep_trans](https://cloud.githubusercontent.com/assets/21355219/24354044/665caca0-132b-11e7-827d-9b5e66acfca1.png)
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
# Input "Hill1" image
![khu3](https://cloud.githubusercontent.com/assets/21355219/24354083/853e2cd4-132b-11e7-84f6-d6d152132f48.png)
# Dehazed by proposed CEP
![khu3_cep](https://cloud.githubusercontent.com/assets/21355219/24354080/850bf75a-132b-11e7-99df-e589e10f02c1.png)
# Transmission by proposed CEP
![khu3_cep_trans](https://cloud.githubusercontent.com/assets/21355219/24354081/850e1a58-132b-11e7-8fcc-bb5aa8d28b2a.png)
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
# Input "View" image
![khu6](https://cloud.githubusercontent.com/assets/21355219/24391091/ec27de3a-13c7-11e7-98e9-9fb037d3d0a9.png)
# Dehazed by proposed CEP
![khu6_cep](https://cloud.githubusercontent.com/assets/21355219/24391096/ec31a6a4-13c7-11e7-87d5-3bb711a3ea6a.png)
# Transmission by proposed CEP
![khu6_trans](https://cloud.githubusercontent.com/assets/21355219/24354233/f6a70ee0-132b-11e7-8148-0eae503c5583.png)
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
# Input "Stage" image
![khu1](https://cloud.githubusercontent.com/assets/21355219/24392008/04eeb632-13cd-11e7-881f-9fe2736cc6bc.png)
# Dehazed by proposed CEP
![khu1_cep](https://cloud.githubusercontent.com/assets/21355219/24448257/8b475662-14ae-11e7-8e46-1b9905807914.png)
# Transmission by proposed CEP
![khu1_cep_trans](https://cloud.githubusercontent.com/assets/21355219/24353968/19b81c54-132b-11e7-9b56-012dafc0450c.png)
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
# Input "Hill2" image
![khu5](https://cloud.githubusercontent.com/assets/21355219/24354192/d7864814-132b-11e7-96f7-98b7327baad7.png)
# Dehazed by proposed CEP
![khu5_cep](https://cloud.githubusercontent.com/assets/21355219/24354193/d78696c0-132b-11e7-9921-a5f6faa58f6d.png)
# Transmission by proposed CEP
![khu5_cep_trans](https://cloud.githubusercontent.com/assets/21355219/24354191/d7853df2-132b-11e7-988e-406c3b6a14df.png)
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
# Input "School_road" image
![khu4](https://cloud.githubusercontent.com/assets/21355219/24392032/19d6db38-13cd-11e7-8b6d-dd93cd2eb5ad.png)
# Dehazed by proposed CEP
![khu4_cep](https://cloud.githubusercontent.com/assets/21355219/24448258/8b70a102-14ae-11e7-89c9-194f48aeec68.png)
# Transmission by proposed CEP
![khu4_cep_trans](https://cloud.githubusercontent.com/assets/21355219/24354131/b3774efa-132b-11e7-80a7-2d74365acb1b.png)
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
# Input "Forest" image
![forest_input](https://cloud.githubusercontent.com/assets/21355219/24338271/05f9d5a0-12df-11e7-9eac-bbbb4a71f9ad.png)
# Transmission by proposed CEP
![forest_cep_trans](https://cloud.githubusercontent.com/assets/21355219/24352661/7a25b96c-1325-11e7-8f62-5be667b75ced.png)
# Dehazed by DCP
![forest_dc](https://cloud.githubusercontent.com/assets/21355219/24340534/ec8c5e58-12ed-11e7-95de-e2f4184c4d72.png)
# Dehazed by Haze-line
![forest_hl](https://cloud.githubusercontent.com/assets/21355219/24340592/70837728-12ee-11e7-8e7f-fe142b90d46e.png)
# Dehazed by Color-line
![forest_cl](https://cloud.githubusercontent.com/assets/21355219/24340551/1818da56-12ee-11e7-8279-0dcf71079943.png)
# Dehazed by proposed CEP
![forest_cep](https://cloud.githubusercontent.com/assets/21355219/24483958/7dc69b3c-1536-11e7-83ec-9ddacb0032b0.png)
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
# Input "Mahattan" image
![ny12_input](https://cloud.githubusercontent.com/assets/21355219/24341194/09327394-12f3-11e7-9e83-db132829a4fb.png)
# Transmission by proposed CEP
![ny12_cep_trans](https://cloud.githubusercontent.com/assets/21355219/24352662/7a277518-1325-11e7-922b-6b43e02e3bcd.png)
# Dehazed by DCP
![ny12_dc](https://cloud.githubusercontent.com/assets/21355219/24341191/09322b1e-12f3-11e7-9ab1-f8af385babe5.png)
# Dehazed by Haze-line
![ny12_hl](https://cloud.githubusercontent.com/assets/21355219/24341192/09324b1c-12f3-11e7-9502-c635de7e60df.png)
# Dehazed by Color-line
![ny12_cl](https://cloud.githubusercontent.com/assets/21355219/24341193/09324dba-12f3-11e7-8eb1-29b59ae566c8.png)
# Dehazed by proposed CEP
![ny12_cep](https://cloud.githubusercontent.com/assets/21355219/24341195/09351702-12f3-11e7-8454-43cbf8818e34.png)
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
# Input "Tree" image and transmission by proposed CEP
![tree_input](https://cloud.githubusercontent.com/assets/21355219/24341085/266b29b6-12f2-11e7-8815-16dfa7f33aad.png)
![tree_cep_trans](https://cloud.githubusercontent.com/assets/21355219/24352668/7a4fcb30-1325-11e7-97e1-14594900b3cc.png)
# Dehazed by DCP and Haze-line
![tree_dc](https://cloud.githubusercontent.com/assets/21355219/24341087/266b3a3c-12f2-11e7-835b-efe98118a0d9.png)
![tree_hl](https://cloud.githubusercontent.com/assets/21355219/24341083/266917de-12f2-11e7-908f-bedef8140dd4.png)
# Dehazed by Color-line and proposed CEP
![tree_cl](https://cloud.githubusercontent.com/assets/21355219/24341084/2669774c-12f2-11e7-88e1-9d45cb25979d.png)
![tree_cep](https://cloud.githubusercontent.com/assets/21355219/24398834/dce3484c-13e5-11e7-9520-06e8b6dab1e2.png)
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
# Input "Swan" image
![swan_input](https://cloud.githubusercontent.com/assets/21355219/24341248/5b1146ea-12f3-11e7-8313-af494dd8f37a.png)
# Transmission by proposed CEP
![swan_cep_trans](https://cloud.githubusercontent.com/assets/21355219/24352667/7a4e4d6e-1325-11e7-9dce-8963a13c0d55.png)
# Dehazed by DCP
![swan_dc](https://cloud.githubusercontent.com/assets/21355219/24341246/5b10ef88-12f3-11e7-91bc-0d8818c1bba1.png)
# Dehazed by Haze-line
![swan_hl](https://cloud.githubusercontent.com/assets/21355219/24341250/5b117976-12f3-11e7-9f80-684006254f5b.png)
# Dehazed by Color-line
![swan_cl](https://cloud.githubusercontent.com/assets/21355219/24341249/5b11782c-12f3-11e7-8a84-3edbae7c21b3.png)
# Dehazed by proposed CEP
![swan_cep](https://cloud.githubusercontent.com/assets/21355219/24386103/b324abdc-13a8-11e7-8914-214c04a7704f.png)
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
# Input "Flags" image transmission by proposed CEP
![flags_input](https://cloud.githubusercontent.com/assets/21355219/24341028/bf6d0f7c-12f1-11e7-862e-1b5423c90d1a.png)
![flags_cep_trans](https://cloud.githubusercontent.com/assets/21355219/24352660/7a2595fe-1325-11e7-9a45-26a61261957e.png)
# Dehazed by DCP and Haze-line
![flags_dc](https://cloud.githubusercontent.com/assets/21355219/24341027/bf6a1628-12f1-11e7-87c9-ee1a6597426f.png)
![flags_hl](https://cloud.githubusercontent.com/assets/21355219/24341030/bf71d0fc-12f1-11e7-88aa-adb3436a160a.png)
# Dehazed by Color-line and proposed CEP
![flags_cl](https://cloud.githubusercontent.com/assets/21355219/24341026/bf6600ce-12f1-11e7-8a2e-ad518c07ada9.png)
![flags_cep](https://cloud.githubusercontent.com/assets/21355219/24341029/bf70fdb2-12f1-11e7-9593-a7f9425e8a88.png)
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
# Input "Tiananmen" image
![tiananmen_input](https://cloud.githubusercontent.com/assets/21355219/24340802/eca6be86-12ef-11e7-9bcf-1ff9cef18e91.png)
# Transmission by proposed CEP
![tiananmen_cep_trans](https://cloud.githubusercontent.com/assets/21355219/24352665/7a4e3612-1325-11e7-86e4-d1adb480ae00.png)
# Dehazed by DCP
![tiananmen_dc](https://cloud.githubusercontent.com/assets/21355219/24340804/eca74fcc-12ef-11e7-9510-9dbf5ed6fa05.png)
# Dehazed by Haze-line
![tiananmen_hl](https://cloud.githubusercontent.com/assets/21355219/24340801/eca67a8e-12ef-11e7-9643-7cd876e42006.png)
# Dehazed by Color-line
![tiananmen_cl](https://cloud.githubusercontent.com/assets/21355219/24340803/eca75288-12ef-11e7-89a0-c2f532b22229.png)
# Dehazed by proposed CEP
![tiananmen_cep](https://cloud.githubusercontent.com/assets/21355219/24344367/23b1a2f4-1306-11e7-8ec3-6d65b7ee5783.png)
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
# Input "Cones" image
![cones_input](https://cloud.githubusercontent.com/assets/21355219/24340658/e8ba23d6-12ee-11e7-96ec-7c87e58a7f54.png)
# Transmission by proposed CEP
![cones_cep_trans](https://cloud.githubusercontent.com/assets/21355219/24352658/7a24e1ae-1325-11e7-8caa-b98024bfa20a.png)
# Dehazed by DCP
![cones_dc](https://cloud.githubusercontent.com/assets/21355219/24340666/fded229e-12ee-11e7-93d6-ed6f580503e7.png)
# Dehazed by Haze-line
![cones_hl](https://cloud.githubusercontent.com/assets/21355219/24340681/12600e08-12ef-11e7-9f91-fe7ca988fec9.png)
# Dehazed by Color-line
![cones_cl](https://cloud.githubusercontent.com/assets/21355219/24340671/08721bde-12ef-11e7-97d3-56a97c74e26e.png)
# Dehazed by proposed CEP
![cones_cep](https://cloud.githubusercontent.com/assets/21355219/24340680/125f9630-12ef-11e7-9e1d-a52a457c0616.png)
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
# Input "House" image and transmission by proposed CEP
![house_input](https://cloud.githubusercontent.com/assets/21355219/24340699/356c1900-12ef-11e7-8645-311d2cf12cb2.png)
![house_cep_trans](https://cloud.githubusercontent.com/assets/21355219/24352659/7a254a4a-1325-11e7-887a-5b8aa76bbff1.png)
# Dehazed by DCP and Haze-line
![house_dc](https://cloud.githubusercontent.com/assets/21355219/24340701/356c5e10-12ef-11e7-914e-184fcb63285c.png)
![house_hl](https://cloud.githubusercontent.com/assets/21355219/24340700/356c1888-12ef-11e7-82a2-54fc3594c1d5.png)
# Dehazed by Color-line and proposed CEP
![house_cl](https://cloud.githubusercontent.com/assets/21355219/24340703/356e662e-12ef-11e7-90fd-aebe61acd225.png)
![house_cep](https://cloud.githubusercontent.com/assets/21355219/24399392/899e2cd6-13e7-11e7-94e3-12821cf9ff17.png)
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
# Input "Road" image
![road_input](https://cloud.githubusercontent.com/assets/21355219/24340765/991b916a-12ef-11e7-8c29-087faf44a445.png)
# Transmission by proposed CEP
![road_cep_trans](https://cloud.githubusercontent.com/assets/21355219/24352663/7a299370-1325-11e7-8656-436b20dedb9e.png)
# Dehazed by DCP
![road_dc](https://cloud.githubusercontent.com/assets/21355219/24340763/98ff0b4e-12ef-11e7-8c1d-2d659eca7a2f.png)
# Dehazed by Haze-line
![road_hl](https://cloud.githubusercontent.com/assets/21355219/24340766/991baef2-12ef-11e7-875b-eec52a428abd.png)
# Dehazed by Color-line
![road_cl](https://cloud.githubusercontent.com/assets/21355219/24340762/98d95048-12ef-11e7-9829-45e18b31ae0a.png)
# Dehazed by proposed CEP
![road_cep](https://cloud.githubusercontent.com/assets/21355219/24399393/89c64b9e-13e7-11e7-9198-4538c818931c.png)
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
# Input "Cityscape" image transmission by proposed CEP
![cityscape_input](https://cloud.githubusercontent.com/assets/21355219/24340871/7b2066ee-12f0-11e7-84b3-e6a15b1cf99b.png)
![cityscape_cep_trans](https://cloud.githubusercontent.com/assets/21355219/24352657/7a00feec-1325-11e7-8032-b0debc6b4565.png)
# Dehazed by DCP and Haze-line
![cityscape_dc](https://cloud.githubusercontent.com/assets/21355219/24340867/7b1d0bac-12f0-11e7-9313-e6dfb1a3a352.png)
![cityscape_hl](https://cloud.githubusercontent.com/assets/21355219/24340870/7b1e66c8-12f0-11e7-8776-efa932e890a1.png)
# Dehazed by Color-line and proposed CEP
![cityscape_cl](https://cloud.githubusercontent.com/assets/21355219/24340869/7b1e0980-12f0-11e7-97c0-4472b544cc12.png)
![cityscape_cep](https://cloud.githubusercontent.com/assets/21355219/24398843/e4f2b00e-13e5-11e7-8505-cf80dc9424f9.png)
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
# Input "Train" image
![train_input](https://cloud.githubusercontent.com/assets/21355219/24341127/70c7b448-12f2-11e7-87a6-211672d97774.png)
# Transmission by proposed CEP
![train_cep_trans](https://cloud.githubusercontent.com/assets/21355219/24352666/7a4e7f8c-1325-11e7-99f9-e755195f9d6e.png)
# "Train" image dehazed by DCP
![train_dc](https://cloud.githubusercontent.com/assets/21355219/24341126/70c781a8-12f2-11e7-897b-45ad850ce687.png)
# Dehazed by Haze-line
![train_hl](https://cloud.githubusercontent.com/assets/21355219/24341128/70c85cb8-12f2-11e7-88fa-d9969b39feff.png)
# Dehazed by Color-line
![train_cl](https://cloud.githubusercontent.com/assets/21355219/24341129/70ca0bbc-12f2-11e7-88b5-0f525e780a25.png)
# Dehazed by proposed CEP
![train_cep](https://cloud.githubusercontent.com/assets/21355219/24341125/70c73cfc-12f2-11e7-92d5-f850f951f30f.png)
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
# Input "Canon" image
![canon_input](https://cloud.githubusercontent.com/assets/21355219/24341157/b294e508-12f2-11e7-846a-76802c21aa4d.png)
# Transmission by proposed CEP
![canon_cep_trans](https://cloud.githubusercontent.com/assets/21355219/24352656/79d7e48a-1325-11e7-89ae-5a5812c0d07d.png)
# Dehazed by DCP
![canon_dc](https://cloud.githubusercontent.com/assets/21355219/24341156/b29475dc-12f2-11e7-8f1e-f57728e07402.png)
# Dehazed by Haze-line
![canon_hl](https://cloud.githubusercontent.com/assets/21355219/24341158/b297b666-12f2-11e7-9b11-1fd86a013525.png)
# Dehazed by Color-line
![canon_cl](https://cloud.githubusercontent.com/assets/21355219/24341154/b294364e-12f2-11e7-9208-02ad724572ed.png)
# Dehazed by proposed CEP
![canon_cep](https://cloud.githubusercontent.com/assets/21355219/24398858/e875f1b4-13e5-11e7-8c8b-0b20a4c5fdfb.png)
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
# Input "Stadium" image
![stadium_input](https://cloud.githubusercontent.com/assets/21355219/24341284/9fa91936-12f3-11e7-89d3-a5f84b42d882.png)
# Transmission by proposed CEP
![stadium_cep_trans](https://cloud.githubusercontent.com/assets/21355219/24352664/7a4c88ee-1325-11e7-8148-69ab5488bc13.png)
# Dehazed by DCP
![stadium_dc](https://cloud.githubusercontent.com/assets/21355219/24341285/9fa96bca-12f3-11e7-9e26-3a4550c93972.png)
# Dehazed by Haze-line
![stadium_cl](https://cloud.githubusercontent.com/assets/21355219/24341287/9faa6be2-12f3-11e7-8eba-2ff911e841e4.png)
# Dehazed by Color-line
![stadium_hl](https://cloud.githubusercontent.com/assets/21355219/24341288/9fadf21c-12f3-11e7-97c7-6438190276bb.png)
# Dehazed by proposed CEP
![stadium_cep](https://cloud.githubusercontent.com/assets/21355219/24341286/9fa96df0-12f3-11e7-9f41-b8677874d222.png)







