# How to submit your tip

To submit a tip in the knowledge-base, fork the [repository](https://github.com/ritsrivastava01/TS_TIPS) and add your tip in a new file in the 'tip' folder. 
Add details of your tip in ['tips.json'](https://github.com/ritsrivastava01/TS_TIPS/blob/master/tip.json) in bellow format:
```json
{
  "title": "<Title of tip>",
  "desc": "Shot Description Of Tip",
  "name": "Contributer Name",
  "gitHubUrl": "Contributer Github URL",
  "descFileName":"<your main Tip file name which will put in 'tips folder'>"
  
}
```
**Recommendation of file name**: tip_<Date_Of _Submisssion in ddmmyyyy>.md format. eg :  tip_07122016.md

### Requirements

- The tip should be readable in less than two minutes
- The .md file should follow the [md rules](https://github.com/fletcher/MultiMarkdown/blob/master/Documentation/Markdown%20Syntax.md)

Once your tip is ready, [create a pull request](https://help.github.com/articles/using-pull-requests/)

Now its done!!!

## Notes
If you are using date in your file name, then leave our date as **xxyyzzz**.md.
When PR will approve and ready to mearge, will tell you OR you need to update the date in file name.
Please also [squash](https://davidwalsh.name/squash-commits-git) your commits.

## Tip flow

**Tip proposal** ⇒ **Tip under review** ⇒ **Approvals** ⇒ **Tip ready to merge**

- When you send a tip, it has to pass the review process and while that happens, its status is `under review`.
- After the tip had been reviewed and its approved then the tip is `ready to merge`.

Thats it, your tip will start contributing the the knowledgebase on this open source

# Email your tip
If you are not aware about the the process you can mail me your tip at ritsrivastava@gmail.com with following details:
1. Json data
2. tip file with correct format
and will create the PR for you.

We are looking forward to your contribution!
