# EBPrimer Site

This site is a Hugo port of [UXSoc ADMU's EB Primer site](http://uxsociety.org/apps/primer). It is meant to be a single page site with executive board member position descriptions.

![](images/screenshot.png)

## Adding a executive board member position

Look at the `data/positions` folder to see the executive member position data. Duplicate one of the `toml` files and modify it to your liking.

| toml key | toml value |
-------------------------
| weight | the lower the weight, the closer to the top the position will appear in relation to other positions |
| position | the position of the UXSoc executive member |
| nickname | the nickname of the position
| content | multi-line string written in markdown that describes the position |

```toml
weight = 1
position = "President"
nickname = "The Don"
content = """
There is no contesting that you are the most passionate person in the organization.

Your number one priority is to wrestle rigorously
with the vision and mission of the organization and to convert your
strategy into a portfolio of projects, structures, and systems.

You play a crucial role in making sure everyone in
the organization is growing. Building lasting connections with your
members is essential to your day-to-day. Conversations are your bread
and butter.

You have enough knowledge to define or illustrate what “User Experience”
is for a whole hour using your own examples.

You don’t go a day without reading about latest
trends, concepts, tools and ideas in UX. But you don’t just read. You
have real experience on how it can be implemented across different
domains. You have several UX projects under your belt.

You understand the value of networking and so you go
out of your way to attend and organize different types of meetups. You
forge partnerships with people personally. You are strategic with the
people you go out and meet.

You can manage expectations and motivations from your executive board
and can inspire them to do their best work yet.

Your words have power, and you make good use of them.
You are able to coach people to heights they never imagined they could
reach.

Your leadership style is people-centric. You are not
obsessed about performance. You care more deeply about people’s growth —
professionally and emotionally.

You have proven expertise on communicating,
designing, leading. You have a vision of where you want to go in the
long term and take proactive steps in achieving that vision.

You are able to rally everyone under your cause, infecting them with the same passion you have for UX.

You understand how our UX agenda contributes to
nation-building and how your role is indispensable in forwarding our
cause and changing society.
"""
```

## Credits

Credits for this theme goes fully to Alexis Collado, UX design lodi and cofounder of the User Experience Society. More werpa to you.