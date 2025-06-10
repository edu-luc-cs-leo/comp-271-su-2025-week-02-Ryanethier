# Coding Reflection: WEEK 00 and WEEK 01

## Comparison to your Solutions

After reviewing your posted solutions for WEEK 00 and WEEK 01, I found that while my code achieved the correct functionality, there are a few areas where your implementations were cleaner or more optimized.

In WEEK 00, our `add` methods were fairly similiar in logic—we both created a new array, copied the old elements, added the new one at the end, and reassigned the reference. Your version used more intentional naming (like `temporary`) and offered clearer, more structured comments. Mine worked fine, but I can improve my documentation and naming to make the code easier to follow.

In WEEK 01, I wrote a custom method to find and remove the smallest element from the array. While the method worked correctly and returned the appropriate value, your`getSmallest2()` version had slightly better handling. For example, I accidentally re-copied the smallest element when shifting the second half of the array. Your version avoided this by starting the second loop at `smallest_index + 1`. Your third version, `getSmallest3()`, was especially elegant it reused existing logic and used a ternary operator to return `null` for empty arrays. That’s something I wouldn’t have thought of on my own but want to practice.

## Reflection and Takeaways

Overall, I got a lot right in my humble opinion: my logic worked, the code compiled, and I tested it with reasonable inputs. I can improve my variable naming, spacing, and structure to make things cleaner. I also want to be more intentional with comments. Your examples helped show how concise comments can improve readability.

One area I know I can improve is Markdown itself. I didn’t put much time into learning how to format this `.md` file, and I know it could be more polished. Going forward, I’ll make time to learn Markdown and its structure so my reflections and documentation are more professional. This is the first assignment I actually sat down to learn a bit about the syntax.

Finally, I want to start assignments a little earlier to leave time for review and refinements—especially for commenting, testing edge cases, and avoiding small logic oversights. I’ll check back in on this plan in the next reflection to see if I actually followed through.

