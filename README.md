# thai-characters-for-speakingurl
Allow Thai characters in Slug for `speakingurl.js` (https://github.com/pid/speakingurl)

# Usage

```
import getSlug from "speakingurl";
import thaichars from "./thaichars";

console.log(getSlug("ทดสอบ test", { custom: thaichars )));

// output: ทดสอบ-test
```
