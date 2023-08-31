### Proposal Feedback

8/10

This looks great, but please answer a few clarification questions for full points.

You mention using ResNet, VGG, and Vision Transformer as three different models. First, do you plan to implement these from scratch, or use an existing model implementation? Implementing three different models from scratch might be a substantial amount of work, so I might recommend you start with existing implementations and then rewrite one or two from scratch once you get them running on your data.

Do you plan to train these models from scratch, or use pretrained models that you then fine-tune on your dataset? My biggest concern is that your X-ray dataset has only a few thousand images, and these larger network architectures are usually trained on millions of images. Thus, training your models from scratch might be difficult – but I also don’t know how easily pretrained models adapt to medical image domains. This might be something you need to spend a little bit more time thinking about.

What data augmentation methods are you particularly interested in? 

Please be more specific in your Desired goal #1. What specifically are you trying to ask about the comparison between architectures? How is this different from Desired goal #2? I might recommend that you combine your two Desired goals into one (more specific) goal, and then add a second goal to explore different pretrained models that were trained on different image datasets. For example, a model trained on generic ImageNet data might have some improvements over no pretraining, but a model pretrained on medical data of some sort is likely much better.
