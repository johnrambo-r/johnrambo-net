---
layout: post
title: "Basics of X-Ray Search"
date: 2021-05-21
tags: [Recruiting]
read_time: 3
---

X-Ray Search is one of the buzz words of the last decade, yet not many recruiters are into it. Maybe it is so because of their sourcing priorities or the working model of their teams. But just because you do not have the scope of using a technique, a methodology or a tool, it doesn't mean you should not learn it.

Whether you are a Recruiter, a Sales person, or an Analyst, learning about X-Ray search is kind of fundamental.

X-Ray search keeps improving and getting improvised based on changes in Search Engines. Google has been the preferred choice for X-Ray Search — though you can try this on Bing or any other engine. But we don't have much of a choice here, do we? 😉

## Anatomy of a URL

Before we get into X-Ray search, it is important to understand the parts of a URL. That will give us an idea about what kind of keywords we should use to pull the data we need.

Consider this URL as an example:

```
https://www.linkedin.com/in/johnramborajendran
```

- **https://** — the Scheme. Tells the web server which protocol to use.
- **www** — the subdomain
- **linkedin** — the second-level domain
- **.com** — the top-level domain
- **/in** — the Path (sub-directory or folder)

The Path is what matters most in X-Ray search.

## Why the Path matters

Not all websites store member records under a specific path.

LinkedIn does:

```
linkedin.com/in/johnramborajendran
```

Here, `/in` is where all member profiles are classified. Facebook, on the other hand, treats members, posts, and products the same — no separate folder in the URL.

To check this yourself, go to any social site and visit your own profile. Look at the URL. You'll immediately see if the site classifies you under a particular path or not. This is fundamental when you X-Ray any website.

## Action Time

Let's do an actual X-Ray search for LinkedIn.

**Scenario:** A Recruiter wants to find Python Developers on LinkedIn.

Start broad:

```
site:linkedin.com "python developer"
```

This returns all "Python Developer" related content on LinkedIn — jobs, people, posts, articles. A large pool. Let's narrow it down:

```
site:linkedin.com/in "python developer"
```

Adding `/in` narrows results to people who have mentioned "Python Developer" in their profiles. You may still get some profile suggestions and job postings mixed in. Let's refine further:

```
site:linkedin.com/in "python developer" -dir
```

This removes directory-style listings, leaving mostly actual developer profiles. Now, if we want to target only people who have "Python Developer" in their profile title:

```
site:linkedin.com/in intitle:"python developer" -dir
```

We can also include people who have it in their profile URL:

```
site:linkedin.com/in (intitle:"python developer" OR inurl:"python developer") -dir
```

This mostly filters out Recruiters who mention "Python Developer" in their summary as part of an open jobs list.

Now add location — because most companies still have a preference for local candidates:

```
site:linkedin.com/in (intitle:"python developer" OR inurl:"python developer") (bangalore OR bengaluru) -dir
```

This pulls profiles where the owner has mentioned Bangalore or Bengaluru in their profile or location.

## Conclusion

And that is definitely not the end of what you can do with X-Ray search. I don't want to overwhelm you with too much in the first shot. There's a lot more when it comes to advanced keyword combinations — maybe I'll cover that in a follow-up.

Happy Recruiting!
