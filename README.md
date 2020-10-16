# Increasing Layers of Abstraction

Before we start our journey to Rails, let's pause and discuss the route to get there. We'll first explore two lower-level Ruby web tools: Rack and Sinatra. Rails does *so much* that it might seem like magic. But as a web app developer, we can't rely on magic to see us through. We need to understand everything we're doing at a layer (or two!) deeper than the layer at which we're operating.

Eventually, the magic will break. In other words, your programs will break. If you can't take Rails apart and understand the fundamentals of what's going on, you'll never be able to fix the magic. You may not be entirely comfortable with all of the internals of Rails, but you will know the foundations. Think about auto mechanics. They may not know every part of every car but they know the foundations. They know common features of all cars, and how even the smallest parts connect to other parts. This allows them to diagnose and suggest fixes faster, and gives them a holistic picture of the mechanics of cars which again will guide them towards solutions. 

With Rails, you'll understand how HTTP works and how Rails is able to translate all of the complexities of HTTP and modern web servers into something that is easy to work with. With all its features, it can also be confusing to see how they fit together to make a response to give to the user. In building up to Rails, you'll build a simple version of most Rails features. Once you `require 'rails'` it should feel familiar.

Be prepared! It's going to be hard to go up layers of abstraction. You are no longer just a driver on the web. You are now a maker on the web.
