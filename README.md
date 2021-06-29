# game

这里面记录了我用：canvas+vue写的游戏项目

- wzq.html 是五子棋
- aircraft_war.html 是飞机大战  
  涉及的图片资源`aircraft_war_images`  
  目前实现了有背景层、子弹层、飞机层、生命道具层  
  实现的功能：我的飞机自由移动并发射子弹、随机生成敌方飞机并发射子弹、子弹碰撞均有监测、还有暂停功能、随关卡升级难度升级，飞机子弹数量也伴随增加，过程中还有随机彩蛋事件、支持重玩、计分板  
  未实现手机端适配，没有做飞机碰撞监测，实在不想写了...精力有限

echo "# game" >> README.md  
git init  
git add README.md  
git commit -m "first commit"  
git branch -M main  
git remote add origin https://github.com/lambertlt/game.git  
git push -u origin main

git remote add origin https://github.com/lambertlt/game.git  
git branch -M main  
git push -u origin main  
