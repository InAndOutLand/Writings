#FaceKit

Apple has included twelve unique watch faces with the Apple Watch. However, telling time is not [something that can only be done in a few ways][slo]. So, some people have called for Apple to allow developers to add custom watch faces to watchOS. But, [as others][gruber] have pointed out, this can lead to people with bad tatse creating some watch face that [look awful][gold].

<img src="https://i.imgur.com/6FWuwBp.png"></img>
<img src="https://i.imgur.com/9Y2KwNn.png"></img>
<img src="https://i.imgur.com/4l8JVF3.png"></img>
<img src="https://i.imgur.com/HeqXawE.png"></img>

However, the story of Apple over the past sixteen years has been one of restrictions(especially so with [WatchKit][wk]). So, it is not unreasonable that Apple would make an API that would expose the watch face to developers that has restrictions. Enter FaceKit.

______

##Proposal
FaceKit would have many constraints how custom watch faces would loook to keep the faces in line with the Apple Watch design style. For example, faces would be limited to having a pure black background. Faces would only use the [San Fransisco][sf] font and common watch face elements such as hands and numbers would be Apple provided.

However, even with these limitations developers could still make creative and novel watch faces. Take [Slow Watch][slo] as an example. FaceKit would have no restrictions on the number of hands or the speed of those hands. So, something like Slow Watch could be implemented in FaceKit. And the faces wouldn't have to look like a normal watch, as you can imagine a watch face that looks like a circular progess bar. 
So you can see how FaceKit could allow people to make tasteful custom watch faces with probably very little effort. The examples described above are not the end all be all. With this proposal for FaceKit, the possibilities are endless.



[slo]: https://www.slow-watches.com
[gruber]: http://daringfireball.net/2015/04/custom_watch_faces
[gold]: http://facerepo.com/app/faces/details/how-apple-was-able-to-patent-gold-for-the-apple-14cd2eb4763
[wk]: https://developer.apple.com/watchkit/
[sf]: https://en.wikipedia.org/wiki/San_Francisco_(2014_typeface)
