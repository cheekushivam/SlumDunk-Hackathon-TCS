# SlumDunk-Hackathon-TCS
Hackathon Question Came In TCS Slum Dunk Hackathon (AI)

# Binder link to open notebook in cloud
 * <a href="https://mybinder.org/v2/gh/cheekushivam/SlumDunk-Hackathon-TCS.git/master">Click Here To Open Notebook In Server</a>
 
# Changes need to be done in some cells
1. Replace Encoding from 'windows-1252' to 'utf-8'
2. Changes during conversion i.e replace 

maxVotedSet.NumbeofVotes = maxVotedSet.NumbeofVotes.replace({',': ''}, regex=True) => 
maxVotedSet.NumbeofVotes = maxVotedSet.NumbeofVotes.replace(',', '', regex=True)

pagesSet.NumberofPages = pagesSet.NumberofPages.replace({None:0.0}, regex=True) =>
pagesSet.NumberofPages = pagesSet.NumberofPages.replace('None',0.0, regex=True)
