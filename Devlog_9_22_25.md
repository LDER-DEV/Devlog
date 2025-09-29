Devlog – RC AI Learning Tool
📅- Week of 9/22 - 9/28-
------------------------------
Project focus: Backend development for the RC AI Learning Tool—a platform designed to help future Resilient Coders students track assignments and receive AI-powered tutoring, aiming to address the two-sigma problem in learning.

🛠 What I Worked On
---------------------------
-Integrated Clerk into the backend for user authentication and authorization.

-Implemented middleware to handle Clerk authorization hooks.

-Added role enforcement between two user types: students and admins.

-Used Cursor and Supabase with Row Level Security (RLS) for database testing and enforcing access control.

-Built backend logic for user creation, login, and sign-out via Clerk webhooks.

-Successfully submitted a pull request for the Clerk authorization work.

💡 Learnings
-------------------
-Gained deeper understanding of webhooks and how to test them locally.

-Picked up practical knowledge on proxy tools like LocalTunnel for local webhook testing.

-Discovered Clerk’s Keyless Dev environment, a simpler solution for local testing without proxies.

⚠️ Challenges / Blockers
---------------------------
-Setting up the testing environment for webhooks in Next.js took time—it was my first direct experience with them.

-Getting used to Next.js’ file structure added a small learning curve early in the implementation.
