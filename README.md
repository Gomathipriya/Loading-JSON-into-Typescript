# Loading-JSON-into-Typescript

In typings.d.ts

include

<pre>

declare module "*.json"
{ const value: any;
  export default value;
}

</pre>

Import into Typescript file using

<pre>

import * as data from 'data.json'
var data:string = ('<'any'>'data).name;

</pre>
