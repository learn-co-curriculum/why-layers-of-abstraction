# Increasing Layers Of Abstraction

Before we begin down the journey to Rails, let's take a quick pause and discuss the route we will take to get there. Before getting to Rails, we are going to pass through two lower-level Ruby web tools: Rack and Sinatra. Rails does *so much* for you that it can appear as magic. As a developer of web apps, we can't just rely on magic to see us through. We have to understand everything we are doing at a layer (or two!) deeper than the layer we are operating.

Eventually, the magic will break. If you are unable to take Rails apart and understand the fundamentals of what is going on, you'll never be able to fix the magic. You may not be entirely comfortable with all of the internals of Rails, but you will know the foundation. You will understand how HTTP works, and how Rails is able to translate all of the complexities of HTTP and modern web servers into something that is easier to work with. Finally, with all of the features of Rails it can get very confusing how the fit together to make a response to give to the user. By building up to Rails you'll have built a simple version of most Rails features. Once you `require 'rails'` it should feel familiar.

While, not all auto mechanics know every part of every car they understand the basics. They know the common features of all cars and an understanding the base workings of the entire car allows them to diagnose and suggest fixes faster. Even when working on the smallest parts of an engine. Understanding how that part connects to other parts gives mechanics a holistic picture that guides them towards solutions.

Be prepared, it's going to be hard to go up layers of abstraction. You are no longer just a driver on the web. You are a maker on the web.
