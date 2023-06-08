# Technical Support Engineer Hiring Project

Hello! This is a hiring project for our Technical Support Engineer role.  If you apply, we'll ask you to do this project so we can see how you work through type of work you'd do at Pinecone.

## Hiring Project: Technical Challenge

Our customers are developers. They usually need support when things are going wrong. In many ways, they're looking less for answers and more for empathy and understanding. Don't get us wrong, they want answers too. But they're happiest when they talk to people who understand what they're going through.

The first part of the hiring process is a technical challenge. We want you to do two things with the starter Pinecone semantic search project in this repository:

1. Create an index using the datasets in the notebook. 
2. Run some sample queries and provide the responses you get from them. 

You don't have to build a pretty front end, you can just use the notebook. If you're never used a Jupyter notebook before [this site gives a good intro to using them](https://docs.jupyter.org/en/latest/install.html). Your queries to the index should include things like:

* What is the highest mountain in the world?
* Who was the first president of the US?
* When did WWII end?

Provide the questions as well as the top three responses for each in your submission.

## Hiring Project: Customer Interaction

We interact with customers in two ways: over email, and in our public discussion forums (we also use Slack for some customers but we're ignoring that for now). We want you to write a sample response for working with a customer in a written medium. For our purposes today, we'll use email. 

### Support Ticket Response

Paid customers use our [Support Portal](https://support.pinecone.io) or email for support. Either way, when a paid customer opens a ticket, we want to do two things:

1. Greet them with a helpful response in a timely manner
2. Investigate their issue

A paid customer reports that they made a small change to their app and now queries are failing. When they run a query, they get the following message: 

```text
Error Message: 
Server error: 500 Internal Server Error. Text: "{"code":13,"message":"We were unable to process your request. If the problem persists, please contact us at support@pinecone.io","details":[]}"
```

Write an initial response to the customer. This might be a problem they can solve, so it would be good to give them some pointers. It's ok to ask them questions about their app, too.

Then, write some notes about how you'd investigate their issue in parallel. If we can figure out what's wrong with a paid customer's index or queries, they'll be happy when we tell 'em. If we discover it's an issue on our end, they'll be happy when we fix it. Win win.

Investigating a customer issue can get complicated. Here are some tools you can use to investigate customer issues:

* Google 
* [The Support KB](https://support.pinecone.io/hc/en-us)
* [Community forums](https://community.pinecone.io) 
* [Our documentation](https://docs.pinecone.io)
* On-call Pinecone product engineers. 
* On-call Pinecone operations engineers.

### Community Forum Response

A community member posted this question:

> I tried to create a new index but when I go to upsert vectors I get an error saying the index name is incorrect. Is Pinecone down or something? 

There are no known outages (if there were, we'd post them on status.pinecone.io). Please write a forum response for this user. Keep in mind that forum responses will be public in real life! You're writing for everyone who will ever read this post.

We have some rough internal guidelines we use for forum posts. Here they are:

Community support should mainly be for community members to help each other out. 
Our job in community is to:

* give users the tools they need to troubleshoot/resolve their own issues
* point users in the right direction by linking docs or other community posts
* "train" users to be better community members

We should not be promising things to users, don't tell them you will look into an issue unless you have already determined it to be on our end and we are working on it, don't tell them something might be a feature later on, get used to saying "no."

You also do not need to spend an inordinate amount of time trying to solve a user's issue, take your time to decide if this is an issue on our end, and if it is not and you have given the user some tools to solve it themselves, it is okay to let them go on their own, other community members will also jump in if they feel they can help and we should be encouraging this. The best way to encourage users to help themselves/others is to get out of their way.

## What we care about

Your writing and code do not need to be perfect. We get that you have a life outside of work. What we're looking for is:

* The ability to reason about customer problems
* Google skills
* Writing so that developers will understand what is written
* Just enough Python or JS skills to get by and provide examples

Do not spend time on:

* Multiple edits to your writing
* Code tests

If you've ever written Python before, we expect the notebook challenge to take about 30 minutes. You can spend as long as you need, though, don't stress if you're learning on the fly.

We think the written responses should take about 1.5 hours total. When we write responses to customers, we usually spend about 10 minutes each. We're not immune to typos ether.

## Submitting your work

We'll invite you to a private GitHub repo based on this template. 

Do all of your work in the `main` branch. Don't bother with PRs, branches, or spend time on tidy commits -- we have software to help us review. Just don't force push over the initial commit or we can't generate a diff of only your work.

Add your written responses and a link to your deployed notebook in [RESPONSES.md](RESPONSES.md). If you don't deploy the notebook outside of the repo, don't worry, you can just make a note of that in the RESPONSES.md. We assume you'll clone it to Collab or Databricks but you don't have to.

When you're ready, let us know and we'll schedule it for review.

We review submissions several times a week. You'll hear back from us no matter what no later than the end of the _following_ week, but probably sooner if you submit early in the week.
