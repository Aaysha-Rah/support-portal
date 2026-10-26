# Developer handoff notes

## What I delivered
I built a static customer support page for Northstar Services with a contact section that lists the support email and the support hours (Monday through Friday, 9 a.m. to 5 p.m. Central Time). To meet the product manager's request, I added a reminder to include an order number when contacting support, and a Frequently Asked Questions section that explains how to check an order's status by signing in and opening the Orders page. I also added a support checklist file.

## How I verified the page
I opened index.html in my browser and confirmed that the styling loaded. I checked that the contact email is visible, the support hours include Central Time, the order number reminder appears, and the FAQ explains where to find order status. I also resized the browser window to a narrow width and confirmed that the page was still readable. All checks passed.

## Remote change I received
A teammate (simulated by me on GitHub.com) added a "Support escalation" section to the README, explaining that unresolved billing requests go to the billing team after one business day. My local copy did not have this change until I ran git pull --ff-only origin main, which downloaded the commit and updated my README.

## Git workflow explanation
git commit only saves a snapshot of my changes in my local repository on my computer. GitHub doesn't know about that commit until I run git push, which sends my local commits to the remote repository. That's why my new files didn't show up on GitHub after the first commit and only appeared after I pushed.