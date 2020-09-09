---
title: "A peek at Kybern.org"
teaser: "I'm writing up some documentation for Concord in preparation for making the project public.  Here's a section with some screenshots of Concord implemented on Kybern.org, demonstrating how you might use the platform."
categories:
  - governance
  - projects
---

I'm writing up some documentation for Concord in preparation for making the project public.  Here's a section with some screenshots of Concord implemented on Kybern.org, demonstrating how you might use the platform:

1: A user creates a new group.  By default, she is added as both owner and governor:

![screenshot]({{ site.url }}/assets/kybern/from_docs/1_create_group.gif)

2: The user, using her governing permission, adds new members to the group.

![screenshot]({{ site.url }}/assets/kybern/from_docs/2_add_members.gif)

3: The user, using her governing permission, creates new roles and adds those new members to roles.

![screenshot]({{ site.url }}/assets/kybern/from_docs/3_add_roles_and_members_to_roles.gif)

4: The user assigns one of the roles, voting members, to be the new owner.  She adds a voting condition.

![screenshot]({{ site.url }}/assets/kybern/from_docs/4_change_owners.gif)

5: The user gives the other role, general members, permission to change the description of the group.  She adds an approval condition from a voting member.

![screenshot]({{ site.url }}/assets/kybern/from_docs/5_add_general_member_permission.gif)

6: A general member tries to change the name of the group.  There’s a condition on their action.  We go to the action history and see that it’s waiting.

![screenshot]({{ site.url }}/assets/kybern/from_docs/6_cant_change_name.gif)

7: A voting member goes and has the ability.  They approve.  We check and see that the action is implemented and the name is different now.

![screenshot]({{ site.url }}/assets/kybern/from_docs/7_name_changed.gif)

And, while I'm showing you all images, here's a new resource type added to Kybern last week - the list:

![screenshot]({{ site.url }}/assets/kybern/from_docs/enhanced_simple_list.gif)