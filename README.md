# demo908

the purpose of the demo 8/5/2019 is to interact with subtrees

we have a repo for common code
and multiple projects that each use a "subtree" to reference that common code


## instructions

here in the "a" directory are a couple of applications for Mac.  the sourceforge one seems best; fork is good, too, even if its interface is less intuitive.

jump into the Terminal and paste this chunk to grab the repositories we'll be working with:


mkdir -p ~/tmp/git_demo_90805 && cd ~/tmp/git_demo_90805 ;
git clone https://github.com/spe-bfountain/demo908_common.git c ;
git clone https://github.com/spe-bfountain/demo908_proj1.git p1 ;
git clone https://github.com/spe-bfountain/demo908_proj2.git p2 ;
git clone https://github.com/spe-bfountain/demo908_proj3.git p3 ;
tree ;

