<a name="module_tc"></a>

## tc
Collection of small Topcoder-related functions.

**Todo**

- [ ] More TC-related utils should be moved here from Community-app.


* [tc](#module_tc)
    * [.REVIEW_OPPORTUNITY_TYPES](#module_tc.REVIEW_OPPORTUNITY_TYPES)
    * [.getApiResponsePayloadV3(res)](#module_tc.getApiResponsePayloadV3) ⇒ <code>Promise</code>

<a name="module_tc.REVIEW_OPPORTUNITY_TYPES"></a>

### tc.REVIEW_OPPORTUNITY_TYPES
Review Opportunity types

**Kind**: static constant of [<code>tc</code>](#module_tc)  
<a name="module_tc.getApiResponsePayloadV3"></a>

### tc.getApiResponsePayloadV3(res) ⇒ <code>Promise</code>
Gets payload from a standard success response from TC API v3; or throws
an error in case of a failure response.

**Kind**: static method of [<code>tc</code>](#module_tc)  
**Returns**: <code>Promise</code> - Resolves to the payload.  

| Param | Type |
| --- | --- |
| res | <code>Object</code> | 

