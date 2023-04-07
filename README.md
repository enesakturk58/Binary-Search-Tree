# Binary-Search-Tree

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.


           -> İlk 5'den başladım çünkü sağındaki oluşacak değerler ile solundaki oluşacak değerlerin sayısının birbirine en yakın olmasını istedim.

Binary Searc Tree oluşumu :

      İlk önce 5'i root olarak alıyorum.

                      5

      1. veri (7), 5'den büyük olduğu için 7'yi 5'in sağına alıyorum.

                      5
                        7

      2. veriyi ilk başta root olarak almıştım. Bunun index'le bir alakası yok. Sebebini yukarıda "->" ile gösterilen yerde belirttim.

      3. veri (1), 5 den küçük olduğu için 1'i 5'in soluna alıyorum.

                      5
                    1   7 

      4. veriyi (8), 5 den büyük olduğu için 5'in sağ tarafına geçiyorum ve 7'den de büyük olduğu için 7'nin de sağ tarafına alıyorum.

                      5
                    1   7 
                          8

      5. veriyi (3), 5'den küçük olduğu için 5'in sol tarafına geçiyorum ve 1'den de büyük olduğu için 1'in sağ tarafına alıyorum.

                            5
                    1               7 
                        3               8

      6. veriyi (6), 5'den büyük olduğu için 5'in sağ tarafına geçiyorum ve 7'den de küçük olduğu için 7'in sol tarafına alıyorum.

                            5
                    1               7 
                        3       6       8

      7. veriyi (0), 5'den küçük olduğu için 5'in sol tarafına geçiyorum ve 1'den de küçük olduğu için 1'in sol tarafına alıyorum.

                            5
                    1               7 
                0       3       6       8


      8. veriyi (9), 5'den büyük olduğu için 5'in sağ tarafına geçiyorum ve 7'den ve 8'den büyük olduğu için 8'in sağ tarafına alıyorum.

                            5
                    1               7 
                0       3       6       8
                                            9

      9. veriyi (4), 5'den küçük olduğu için 5'in sol tarafına geçiyorum ve 1'den ve 3'den büyük olduğu için 3'ün sağ tarafına alıyorum.

                                  5
                    1                         7 
                0       3                 6       8
                           4                          9

      10. veriyi (2), 5'den küçük olduğu için 5'in sol tarafına geçiyorum ve 1'den büyük ve 3'den küçük olduğu için 3'ün sol tarafına alıyorum.

                                  5
                    1                         7 
                0       3                 6       8
                     2     4                          9

                              




