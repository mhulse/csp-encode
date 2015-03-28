# CSP Encode

### Encode: A Caché RULE (aka CSP tag) that convert all applicable characters to HTML entities.

---

#### EXAMPLES

**See also:** [`test.csp`](https://github.com/mhulse/csp-enqueue/blob/master/enqueue/test.csp).

---

#### NOTES:

Non-[DTI](http://www.dtint.com/) customers should emove these lines from `custom.rg.EncodeRule.csr`:

```
<csr:class super="dt.common.page.Rule" />
```

```
<script language="cache" runat="compiler">
	do ##this.RenderDTStartTag()
</script>
```

```
<script language="cache" runat="compiler">
	do ##this.RenderDTEndTag()
</script>
```

---

#### LEGAL

Copyright © 2012 [Micky Hulse](http://mky.io)

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this work except in compliance with the License. You may obtain a copy of the License in the LICENSE file, or at:

[http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
