**If you're contracting for an A or a B, this is your Topic Check-in. Write a short paragraph describing your idea and where the data will come from, and include a link to your project repository. Use the Project Scaffold Table from the README template to organize your plan.**

Top Instagram Influential Categories By Follower Counts

**Topic / Question - What real-world question are you investigating, and why does it matter?**
What type of accounts have the most influence on Instagram by follower counts? Are certain categories like Sport or Music more influential than others by follower counts, and by how much?

Today's society is spending much of their time on social media platforms like Instagram and being influenced by the content shared there. Famous accounts and organizations can easily reach and influence millions of people. It would be interesting to analyze the difference between average follower counts across different categories to understand which types of accounts hold the most influence.

**Hypothesis - What do you expect to find? State a clear, testable hypothesis.**
Since music is a widely consumed form of entertainment, my hypothesis is that Music accounts will have higher average follower counts compared to non-Music accounts.

**Outcome / Metric / Test Statistic - What variable(s) or statistic(s) will you analyze?**
The primary variables are the `followers` and `category` of each Instagram account.

The statistic of interest is the difference in average follower count between Music accounts and non-Music accounts.

**Units of Analysis - What does each observation represent?**
Each observation represents a single Instagram account, including its follower count and category.

**Data Source(s) - Where will your data come from? Include links or access notes.**
The dataset comes from Instagram Top Accounts https://github.com/FastSocialCo/instagram-top-accounts/tree/main. Specifically, I will use the `data/latest.csv` file for the latest data on follower counts and categories of Instagram accounts.

**Why this data works - How is the dataset appropriate for your question?**
The dataset contains the latest data pull of the most-followed public Instagram accounts, including their follower counts and categories. This is the official data source behind the information provided by FastSocial.

**Uncertainty Metric - Which variable will you use bootstrapping for?**
I will use bootstrapping for the difference in average follower counts between Music accounts and non-Music accounts to estimate the uncertainty of this difference.

**Null Hypothesis - In plain English, what would it mean if there were no effect?**
The null hypothesis is that there is no difference in average follower counts between Music accounts and non-Music accounts on Instagram. Any observed difference would be due to random variation rather than a true effect.