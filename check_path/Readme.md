- 8-2CP_epoch135.pth   训练:验证=8:2,数据为冠脉数据，无微调
- 8-2CP_epoch150.pth

- CP_epoch150tunningbe.pth   视网膜参数
- CP_epoch80.pth 去掉了多gpu训练，重新训练的视网膜
- CP_epoch80_DRIVE40.pth   40个视网膜，epoch80, lr=10e-3 
- CP_epoch40_DRIVE40.pth      预训练CP_epoch80_DRIVE40.pth， 微调 lr =10e-5

- CP_epoch20.pth 20个epoch 微调，全部训练（分类器未传入）
- CP_epoch40.pth 40个epoch 微调，全部训练（分类器未传入）lr=10e-6
- CP_epoch40_300+.pth 微调，增加样本后重新训练 lr=10e-6
- CP_epoch150_300+.pth 增加样本后直接训练 lr=10e-3
- CP_epoch150_300.pth 增加样本,打乱样本后直接训练 lr=10e-3

- CP_epoch150.pth 直接训练冠脉
- 传入视网膜参数化，全部层重新训练
- alltrain_CP_epoch135.pth   150epoch  lr 10-3  10-4 10-5
- alltrain_CP_epoch150.pth   150epoch  lr 10-3  10-4 10-5

- alltrain_CP_epoch200.pth    200epoch lr 0.1, 0.001, 0.0001, 0.00001

- alltrain_CP_epoch300.pth   300epoch  lr  10-1  10-2  10-3  10-4  -5 -6   