---
layout: post
title: "Comment Structure"
date: 2021-01-05
category: comments
author: Velnota
short-description: Design Layout of Comments
---

-----

The comment structure is similar to YouTube's original
comment section. There's an original **comment** which
includes several chronologically ordered **replies**.

![A comment section](/assets/screenshots/comment-structure.png)
{: .img-responsive-md}

Right now, you only see the comments, but you haven't seen the
replies. To see the replies, press the "View Reply" button.
it may include a number. If it is grayed out, it means the comment
hasn't gotten any replies yet.

Comments are ordered by -- default -- an "Interesting" filter.
You can change the order of the root comments by heading to the
comment box and clicking on "Sort By":

![Comment Box](/assets/screenshots/comment-box.png)
{: .img-responsive-md}

You can choose either the "Interesting" filter, the latest comments,
or the oldest comments to view.

---
### Design Principles

We wanted to design the comment section like this because we saw
how conversations were generated in a fluid motion. When people
read a full thread, they'll get the start-to-finish story of what
comment or critique a reply may have posed.

We wanted the comment section to generate conversations, and we tried
our best to design the comment section as fluid as possible, like any
normal conversation. There were two possibilities:

1. Use the parent-child comment thread. This allows for fluid conversations
   between multiple users without breaking up the context too much.
2. Use the tree comment design. The tree design concept is seen at Reddit,
   but we didn't like that design because that lost the conversational tone.
   Users would bounce around from conversation thread to thread.

#### Notes

- The Interesting filter is still based on Reddit's comment filter system!
  Although the designs between us are different, the scoring is better than
  a generic up/down scoring system.
- We wanted to show both the oldest and latest comments so that we
  could compare what people say 4 years ago from now.
