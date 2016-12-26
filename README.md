# Running-Circle
**loding Animation 旋转圈**
- 1.现在View上创建一个小圆圈，并给这个圆圈添加Animation和3D变换
- 2.然后再用CAReplicatorLayer这个类复制多个同样的圆，并设置圆的位置和3D变换
### 使用方法

**- 1.通过在_circleView上调用showAtCenterWithSize:创建**

- (void)showdefautRoundAnimation
- {
-         [_circleView showAtCenterWithSize:CGSizeMake((kScreenWidth-76)*0.67, (kScreenWidth-76)*0.77)];  
- }

**- 2. 开始和结束动画**
  - [self showdefautRoundAnimation];  //开始动画
    
  - [_circleView endCustionAnimation];  //结束动画
  
  如下图外圈旋转小圆点：
  ![image](http://ois78ab8t.bkt.clouddn.com/aa.png)
