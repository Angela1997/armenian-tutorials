# GIT հրամաններ

## Ֆայլերի ինդեքսավորում
**git add** *.*			- Ինդեքսավորում է բոլոր փոփոխված ֆայլերը  
**git add** *file*			- ավելացնում է file ֆայլը  
**git add** *file1* *file2*		- ավելացնում է file1 եւ file2 ֆայլերը  

## Ֆայլերի ջնջում
**git rm** *file*			- ջնջում է file ֆայլը  
**git rm** *file1* *file2*			- ջնջում է file1 եւ file2 ֆայլերը  

## Ֆայլերի վերբեռնում
**git pull**				- commit արված ֆայլերն ուղարկում է remote master branch  
**git pull** *origin* *branch*	 	- commit արված ֆայլերն ուղարկում է remote branch branch  

## Ֆայլերի ներբեռնում
**git push**			- remote master branch-ից բեռնում է փոփոխությունները  
**git push** *origin* *branch*		- remote branch branch-ից բեռնում է փոփոխությունները  

## Branch-ների փոխատեղում
**git checkout -b** *branch*		- ստեղծում է նոր branch անվանումով նոր branch  
**git checkout** *branch*		- անցում է կատարում արդեն առկա branch անվանումով branch  

##Այլ հրամաններ
**git clone** *repositoryURL*	- կլոնավորում է repositoryURL հասցեից remote master branchgit commit -m 'text'		- ինդեքսավորված ֆայլերին տալիս է text մեկնաբանությունը  
**git status**			- ցույց է տալիս ընթացիկ փոփոխված ֆայերի ցանկը  
**git init**				- Ինիցիալիզացնում նոր repository  
**git diff**				- ցուցադրում է փոփոխությունները  
**git branch**			- ցուցադրում է local branch-երի ցանկը  

## Պարզագույն հրամանների օգտագործման օրինակներ
**git clone** *https://github.com/username/repository*  
**cd** *repository*  
**git checkout -b** *new-branch-name*  
**git add** *.*   
**git commit -m** *'compiler: bug fixes'*  
**git push origin** *new-branch-name*  

Հրաման  | Նշանակություն
------------- | -------------
**git add** *.*  | Ինդեքսավորում է բոլոր փոփոխված ֆայլավելացնում է file ֆայլը  Content Cell
**git add** *file1* *file2*  | ավելացնում է file1 եւ file2 ֆայլերը  