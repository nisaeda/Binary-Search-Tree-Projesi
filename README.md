# Binary-Search-Tree-Projesi
www.patika.dev
# [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
- İlk olarak roota karar vermemiz gerekir. En baştan ilk üç sayının 7 5 1 olduğunu görüyoruz. Eğer rootu 5 seçersek; 1 roottan küçük olduğundan soluna, 7 roottan büyük olduğundan sağına gelecektir.
- 8, 7'den büyük olduğundan sağına gelecektir.
- 3, 1'den büyük olduğundan sağına gelecektir. 
- 6, 7'den küçük olduğundan soluna gelecektir. Aynı zamanda roottan büyüktür ve 5'İn sağında kaldığını da görmüş oluruz.
- 0, 1'den küçük olduğundan soluna gelecektir.
- 9, 7den büyük ve 8den büyük olduğundan 8'in sağına eklenecektir.
- 4, 3'ten büyük olduğundan sağına eklenecektir.
- 2, 3'ten küçük olduğundan soluna eklenecektir.
# Bu durumda son hali aşağıdaki gibi olacaktır;
-                             5
-                   1                   7
-              0        3           6        8
-                   2       4                     9                    
