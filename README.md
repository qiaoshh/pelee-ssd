This repository aim at multi objects detection by pelee based ssd.\n
Useage:
1. git clone the repository, note: dataset use VOC format
2. mkdir build && cd build
3. cmake ..
4. make -j8
5. make pycaffe
6. convert VOC dataset to lmdb by python scripts(creat_list.sh and create_data.sh)
7. modify train.prototex, test.prototxt, solver.prototxt and train_pelee_ssd_dc.sh by your own work.
8. above all finish, run"./train_pelee_ssd_dc.sh" start training!

