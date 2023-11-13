# section-page.md: A page containing sections
This is an experimental version.
Note that link names are shown when clicking the link icon in the github editor preview, but are not shown for link names defined by a '<a' id="name">description'</a>' sequence.

- [go to Allocator::get](#get)
- [go to Allocator::debug](#virtual-void-debugconst-char-info-nullptr)
- [go to BlockAllocator::get](#b_get)

## section1
blah, blah, blah. 

## section2
blah, blah, blah. 

## section3
blah, blah, blah. 

## name 
This section's name is duplicated.

## name 
This section's name is duplicated.

<!-- --------------------------------------------------------------------- -->
## Sample that's supposed to work:
## Title

### Place 1

Hello, this is some text to fill in this, [here](#place-2), is a link to the second place.
Let's add a [link to place3](#places-3-other-example) just for fun.

### Place 2

Place one has the fun times of linking here, but I can also link back [here](#place-1).

### Place's 3: other example

Place one has the fun times of linking here, but I can also link back [here](#places-3-other-example).

<!-- --------------------------------------------------------------------- -->

## Actual page with sections.
The following markdown was used to provide link targets. It's been edited so all the text is just "blah, blah, blah."  

<!-- -------------------------------------------------------------------------
blah, blah, blah.
-------------------------------------------------------------------------- -->
###### Defined in header <pub/Allocator.h>
blah, blah, blah.

---

## pub::Allocator:: check, debug, get, put
blah, blah, blah.

####
---
#### Allocator( void ) = default;
#### virtual ~Allocator( void ) = default;
blah, blah, blah.

---
#### virtual int check( void );
blah, blah, blah.

---
#### virtual void debug(const char* info= nullptr);
blah, blah, blah.

---

#### <a id="get">virtual void* get(size_t size=0);</a>
blah, blah, blah.

---

#### <a id="put">virtual void put(void* addr, size_t size=0);</a>
blah, blah, blah.

---

## <a id="blockallocator">BlockAllocator:: get, put</a>
blah, blah, blah.

####
---
#### BlockAllocator(size_t size, size_t b_size);
blah, blah, blah.

---
#### virtual ~BlockAllocator( void );
blah, blah, blah.

---
#### <a id="b_get">virtual void* get(size_t size=0);</a>
blah, blah, blah.

---
#### <a id="b_get">virtual void* get(size_t size=0);</a>
blah, blah, blah.

---
#### <a id="b_put">virtual void put(void* addr, size_t size=0);</a>
blah, blah, blah.

---
#### virtual void* alpha(size_t size=0);</a>
blah, blah, blah. (Just to take up space.)

---
#### virtual void* beta(size_t size=0);</a>
blah, blah, blah. (Just to take up space.)

---
#### virtual void* gamma(size_t size=0);</a>
blah, blah, blah. (Just to take up space.)

---
