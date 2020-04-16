# 项目路径说明：

根目录下分为三个文件夹：code，data，papers。后续试验过程建议将data路径设置为项目根目录下的data文件夹。

code文件夹中根据项目可新建文件夹。如后续使用复现的论文或模型可使用该模型的关键字信息命名文件夹。目前仅有baseline一个文件夹。

data/train_data/文件夹中由于train_data.json太大，所以只上传了zip文件，需自行解压缩。

# ignore 说明

目前ignore的文件包括：

~~~
*.DS_Store
*.pyc
*checkpoint.ipynb
.mypy_cache*
code/baseline/pretrained_model
~~~~

首次上传项目包含数据文件，后续过程中会将 .json文件也ignore掉。

# 分支

建议使用自己名字新建分支。新建分支以及第一次上传命令可参考：

~~~
git branch wuduo #本地新建分支
git checkout wuduo #本地切换分支
echo "test" > wuduo_test_branch
git add .
git commit -m "wuduo test branch"
git push --set-upstream origin wuduo #建立上游分支的跟踪并完成push。
~~~~
