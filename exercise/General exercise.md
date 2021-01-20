# General exercise
1. Explain the difference between cookies, session storage, and local storage?

Ans: 

LocalStorage
- The data which stores without expiration date. It will get cleared only through JavaScript, or clear browser cache manually.

SessionStorage
- Storage limit is at least 5MB.
- The data is stored until the browser is closed.

Cookie
- Its expiration can be set from either server-side or client-side.
- Size must be less than 4KB.

The difference sees below:
- LocalStorage is the maximum amongst the three.
- Cookies are primarily for server-side reading, the rest can only be read on client-side.
- If the browser is closed, SessionStorage data will get cleared.
There is an expiration for Cookies, not for LocalStorage until clear it manually.

2. What does CORS stand for and what issue does it address?
Cross-origin resource sharing is a mechanism that allows restricted resources on a web page to be requested from another domain outside the domain from which the first resouce was served.
If the access is blocked by CORS policy, the issue will be the Response to preflight request doesn't pass access control check: NO 'Access-Control-Allow-Origin' header is present on the requested resource.

3. What is HTTP method OPTIONS?
The OPTIONS method represents a request for information about the communication options available on the request/response chain identified by the Request-URI. This method allows the client to determine the options and/or requirements associated with a resource, or the capabilities of a server, without implying a resource action or initiating a resource retrieval.

4. Describe BFC (Block Formatting Context) and how it works.
Floats, absolutely positioned elements, block containers (such as inline-blocks, table-cells, and table-captions) that are not block boxes, and block boxes with 'overflow' other than 'visible' (except when that value has been propagated to the viewport) establish new block formatting contexts for their contents.

In a block formatting context, boxes are laid out one after the other, vertically, beginning at the top of a containing block. The vertical distance between two sibling boxes is determined by the 'margin' properties. Vertical margins between adjacent block-level boxes in a block formatting context collapse.

In a block formatting context, each box's left outer edge touches the left edge of the containing block (for right-to-left formatting, right edges touch). This is true even in the presence of floats (although a box's line boxes may shrink due to the floats), unless the box establishes a new block formatting context (in which case the box itself may become narrower due to the floats).

5. Explain the difference between layout, painting and compositing.
- layout: the way in which the parts of something are arranged or laid out.
- painting:  its the action of using paint, to create a graphic. Yes, painting is a graphic and so is a photograph and a typeface.
- Composition: combining two or more images/elements to make a single graphic is composition.

6. Can you explain the difference between px, em and rem as they relate to font sizing?
- px: the font sizing is absolutely fixed despite the user's screen width.
- em: the font sizing is relatively to the element.
- rem the font sizing is relatively to the root element.

7. What tools would you use to find a performance bug in your code?
I would use developer tools built in web browsers especially chrome's devTools.The reason is I can using alert() or console.log() to perform. Also I couls pause code execution with the debugger as the breakpoint which allows me to investigate the bug occurs.

