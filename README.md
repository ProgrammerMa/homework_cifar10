# homework_cifar10

## 实验方法
batch_size固定为16，学习率lr的值固定为0.001

通过改变超参数epoch的值，分析模型在训练过程中loss值的变化
### epoch=10
```buildoutcfg
[1,  2000] loss: 1.967
[2,  2000] loss: 1.497
[3,  2000] loss: 1.327
[4,  2000] loss: 1.214
[5,  2000] loss: 1.127
[6,  2000] loss: 1.072
[7,  2000] loss: 1.019
[8,  2000] loss: 0.972
[9,  2000] loss: 0.923
[10,  2000] loss: 0.884
Finished Training
GroundTruth:    cat  ship  ship plane
Predicted:    cat   car   car plane
Accuracy of the network on the 10000 test images: 63 %
Accuracy of plane : 65 %
Accuracy of   car : 74 %
Accuracy of  bird : 50 %
Accuracy of   cat : 37 %
Accuracy of  deer : 56 %
Accuracy of   dog : 49 %
Accuracy of  frog : 77 %
Accuracy of horse : 71 %
Accuracy of  ship : 74 %
Accuracy of truck : 74 %
```
### epoch=20
```buildoutcfg
[1,  2000] loss: 2.011
[2,  2000] loss: 1.450
[3,  2000] loss: 1.263
[4,  2000] loss: 1.159
[5,  2000] loss: 1.088
[6,  2000] loss: 1.028
[7,  2000] loss: 0.973
[8,  2000] loss: 0.925
[9,  2000] loss: 0.881
[10,  2000] loss: 0.844
[11,  2000] loss: 0.809
[12,  2000] loss: 0.774
[13,  2000] loss: 0.744
[14,  2000] loss: 0.719
[15,  2000] loss: 0.678
[16,  2000] loss: 0.654
[17,  2000] loss: 0.637
[18,  2000] loss: 0.615
[19,  2000] loss: 0.586
[20,  2000] loss: 0.571
Finished Training
GroundTruth:    cat  ship  ship plane
Predicted:    cat plane  ship plane
Accuracy of the network on the 10000 test images: 64 %
Accuracy of plane : 74 %
Accuracy of   car : 81 %
Accuracy of  bird : 55 %
Accuracy of   cat : 43 %
Accuracy of  deer : 50 %
Accuracy of   dog : 50 %
Accuracy of  frog : 77 %
Accuracy of horse : 69 %
Accuracy of  ship : 66 %
Accuracy of truck : 72 %
```
### epoch=30
```buildoutcfg
[1,  2000] loss: 2.031
[2,  2000] loss: 1.480
[3,  2000] loss: 1.310
[4,  2000] loss: 1.211
[5,  2000] loss: 1.139
[6,  2000] loss: 1.075
[7,  2000] loss: 1.031
[8,  2000] loss: 0.979
[9,  2000] loss: 0.946
[10,  2000] loss: 0.908
[11,  2000] loss: 0.864
[12,  2000] loss: 0.833
[13,  2000] loss: 0.795
[14,  2000] loss: 0.770
[15,  2000] loss: 0.741
[16,  2000] loss: 0.714
[17,  2000] loss: 0.682
[18,  2000] loss: 0.662
[19,  2000] loss: 0.642
[20,  2000] loss: 0.617
[21,  2000] loss: 0.593
[22,  2000] loss: 0.574
[23,  2000] loss: 0.558
[24,  2000] loss: 0.543
[25,  2000] loss: 0.523
[26,  2000] loss: 0.505
[27,  2000] loss: 0.488
[28,  2000] loss: 0.476
[29,  2000] loss: 0.467
[30,  2000] loss: 0.447
Finished Training
GroundTruth:    cat  ship  ship plane
Predicted:  plane  ship   car plane
Accuracy of the network on the 10000 test images: 60 %
Accuracy of plane : 56 %
Accuracy of   car : 77 %
Accuracy of  bird : 48 %
Accuracy of   cat : 43 %
Accuracy of  deer : 50 %
Accuracy of   dog : 50 %
Accuracy of  frog : 66 %
Accuracy of horse : 65 %
Accuracy of  ship : 79 %
Accuracy of truck : 69 %
```
### epoch=40
```buildoutcfg
[1,  2000] loss: 1.987
[2,  2000] loss: 1.485
[3,  2000] loss: 1.311
[4,  2000] loss: 1.200
[5,  2000] loss: 1.118
[6,  2000] loss: 1.065
[7,  2000] loss: 0.993
[8,  2000] loss: 0.951
[9,  2000] loss: 0.906
[10,  2000] loss: 0.866
[11,  2000] loss: 0.832
[12,  2000] loss: 0.800
[13,  2000] loss: 0.765
[14,  2000] loss: 0.737
[15,  2000] loss: 0.708
[16,  2000] loss: 0.680
[17,  2000] loss: 0.653
[18,  2000] loss: 0.629
[19,  2000] loss: 0.609
[20,  2000] loss: 0.578
[21,  2000] loss: 0.571
[22,  2000] loss: 0.545
[23,  2000] loss: 0.523
[24,  2000] loss: 0.507
[25,  2000] loss: 0.493
[26,  2000] loss: 0.470
[27,  2000] loss: 0.461
[28,  2000] loss: 0.452
[29,  2000] loss: 0.432
[30,  2000] loss: 0.426
[31,  2000] loss: 0.408
[32,  2000] loss: 0.407
[33,  2000] loss: 0.383
[34,  2000] loss: 0.374
[35,  2000] loss: 0.371
[36,  2000] loss: 0.362
[37,  2000] loss: 0.360
[38,  2000] loss: 0.351
[39,  2000] loss: 0.339
[40,  2000] loss: 0.332
Finished Training
GroundTruth:    cat  ship  ship plane
Predicted:    dog  ship plane plane
Accuracy of the network on the 10000 test images: 60 %
Accuracy of plane : 66 %
Accuracy of   car : 77 %
Accuracy of  bird : 43 %
Accuracy of   cat : 36 %
Accuracy of  deer : 53 %
Accuracy of   dog : 59 %
Accuracy of  frog : 68 %
Accuracy of horse : 65 %
Accuracy of  ship : 69 %
Accuracy of truck : 62 %
```
### epoch=50
```buildoutcfg
[1,  2000] loss: 1.940
[2,  2000] loss: 1.457
[3,  2000] loss: 1.300
[4,  2000] loss: 1.191
[5,  2000] loss: 1.119
[6,  2000] loss: 1.058
[7,  2000] loss: 1.006
[8,  2000] loss: 0.951
[9,  2000] loss: 0.917
[10,  2000] loss: 0.868
[11,  2000] loss: 0.842
[12,  2000] loss: 0.800
[13,  2000] loss: 0.774
[14,  2000] loss: 0.750
[15,  2000] loss: 0.716
[16,  2000] loss: 0.683
[17,  2000] loss: 0.667
[18,  2000] loss: 0.635
[19,  2000] loss: 0.615
[20,  2000] loss: 0.590
[21,  2000] loss: 0.573
[22,  2000] loss: 0.547
[23,  2000] loss: 0.536
[24,  2000] loss: 0.508
[25,  2000] loss: 0.497
[26,  2000] loss: 0.483
[27,  2000] loss: 0.469
[28,  2000] loss: 0.453
[29,  2000] loss: 0.446
[30,  2000] loss: 0.432
[31,  2000] loss: 0.410
[32,  2000] loss: 0.399
[33,  2000] loss: 0.400
[34,  2000] loss: 0.396
[35,  2000] loss: 0.387
[36,  2000] loss: 0.376
[37,  2000] loss: 0.360
[38,  2000] loss: 0.353
[39,  2000] loss: 0.344
[40,  2000] loss: 0.339
[41,  2000] loss: 0.332
[42,  2000] loss: 0.324
[43,  2000] loss: 0.315
[44,  2000] loss: 0.330
[45,  2000] loss: 0.308
[46,  2000] loss: 0.306
[47,  2000] loss: 0.304
[48,  2000] loss: 0.291
[49,  2000] loss: 0.290
[50,  2000] loss: 0.296
Finished Training
GroundTruth:    cat  ship  ship plane
Predicted:   frog  ship  ship plane
Accuracy of the network on the 10000 test images: 60 %
Accuracy of plane : 62 %
Accuracy of   car : 74 %
Accuracy of  bird : 45 %
Accuracy of   cat : 42 %
Accuracy of  deer : 56 %
Accuracy of   dog : 51 %
Accuracy of  frog : 72 %
Accuracy of horse : 63 %
Accuracy of  ship : 73 %
Accuracy of truck : 67 %
```

### 结论
可以看出，epoch值越大，训练集上收敛后的loss值越小，但是测试集上的准确率基本不变。
