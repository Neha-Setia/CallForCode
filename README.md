# CallForCode
### Connecting the DOTS with a Dash!

Remember Remember The fag end of August.
For It’s a must.

God’s own country is in deluge.
People all across are helping huge.
Blankets, clothes and polished  legumes
Still somewhere 
She was stumbling sinking 
Seeking refuge.

It’s Fatal!
It’s Deadly! 
Don’t go, People said.
But the prince was adamant and refused.
Riding between the palm trees 
On sea king 42B, his muse.

In the moment of blues
He painted the sky with red hues.

Remember Remember The fag end of August.
For It’s a must
God’s own country was in deluge.
but the faith is restored, 
In the situation this acute.


This poem written by me refers to the situation in Kerala and how captain P. Rajkumar helped the wheelchair bound pregnant woman by pulling her out from a tiny terrace. 
-----------------------------------------------------------------------------------------------------------------------------

One of many problems faced at the time of disaster is to gather real-time needs of the victims. Kerala( Indian State) is in a deluge for past one month. People all across the country are raising funds and donating the everyday things. But how to keep the rescue teams and the volunteers updated as to where all people need help, and what kind of help? Our solution  connecting the dots with a dash is all about connecting the seekers and the helpers using the knowledge graph on the basis of real time needs. The real time needs and the metadata attached to it like location and other stuff are extracted through live streaming tweets with hashtags like #keralarains,  #keralrainhelp and are fed to Knowledge Graph. The knowledge graph keeps learning and growing as per the live Information. This knowledge graph can queried by rescue team to know where all people need help and what kind of help it will give you the answer. Similarly a seeker can also find who all helping with kind of service they need and they can directly contact them. The solution can be extended to gathering live update from live blogs, live news channels and live satellite Images. 


 ![](/images/architecture.png)


### Run the code
1. Run the python script `gatherTweetsWithHashtag.py` under the section code in the repository. It will start gathering the tweets with those hashtags and will store in the csv file.
2. Take The csv file and run the notebook [`Call for Code`](https://github.com/Neha-Setia/CallForCode/blob/master/code/Call_for_Code.ipynb)on the watson studio, using the configuration file under `configuration folder`. Follow [Query Knowledge Graph code pattern](https://github.com/IBM/query-knowledge-base-with-domain-specific-documents/blob/master/README.md). For the sake of the demo the tweets has been hard-coded but that part can be made dynamic easily.
3. Take the [NodeRed Flow](https://github.com/IBM/query-knowledge-base-with-domain-specific-documents/tree/master/node-red-flow). Create a Node-Red Application. Follow [Orchestrate Node-Red flow](https://developer.ibm.com/code/patterns/orchestrate-data-science-workflows-using-node-red/)
4. Run the application.
