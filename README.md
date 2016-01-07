##New blog
hexo init  

##Recreate
npm install hexo  (hexo-cli)  
npm install hexo-server --save  
git pull origin master  
git branch -r   
git checkout gh-pages  

##MV To Other Theme (some img&config) 
git clone https://github.com/MOxFIVE/hexo-theme-yelee.git themes/yelee  
source/config include imgs/config.xml  

##Generate
hexo generate  
hexo publish  
hexo server [link](http://localhost:4000/)  


##git push origin master 

[hexo doc]: https://hexo.io/docs/server.html  
[hexo theme yelee]: https://github.com/MOxFIVE/hexo-theme-yelee  
[hexo theme next]:  https://github.com/iissnan/hexo-theme-next  
