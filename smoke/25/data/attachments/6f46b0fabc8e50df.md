# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: proposalTestcases/Hana_T243.spec.ts >> Hana_T243 - Wedding Proposal with existing customer Functionality Test
- Location: tests/proposalTestcases/Hana_T243.spec.ts:78:1

# Error details

```
Error: Failed to upload Image 1. Reason: Error: ENOENT: no such file or directory, stat 'testFiles\roses red.jpg'
```

# Page snapshot

```yaml
- generic [ref=e1]:
  - generic [ref=e2]:
    - generic [ref=e3]:
      - generic [ref=e4] [cursor=pointer]:
        - generic [ref=e5]: 
        - generic [ref=e6]: hana
      - list [ref=e8]:
        - listitem [ref=e9] [cursor=pointer]:
          - link "Orders" [ref=e10]:
            - /url: javascript:void(0)
            - generic [ref=e12]: Orders
        - listitem [ref=e13] [cursor=pointer]:
          - link "Customers" [ref=e14]:
            - /url: /Dashboard/CustomerNew
            - generic [ref=e16]: Customers
        - listitem [ref=e17] [cursor=pointer]:
          - link "Marketing" [ref=e18]:
            - /url: javascript:void(0);
            - generic [ref=e20]: Marketing
        - listitem [ref=e21] [cursor=pointer]:
          - link "Configuration" [ref=e22]:
            - /url: javascript:void(0);
            - generic [ref=e24]: Configuration
        - listitem [ref=e25] [cursor=pointer]:
          - link "Proposals (2)" [ref=e26]:
            - /url: /Proposal/Index
            - generic [ref=e28]: Proposals
            - generic [ref=e29]: (2)
        - listitem [ref=e30] [cursor=pointer]:
          - link "Procurement" [ref=e31]:
            - /url: javascript:void(0);
            - generic [ref=e33]: Procurement
        - listitem [ref=e34] [cursor=pointer]:
          - generic [ref=e37]: Reports
        - listitem [ref=e38] [cursor=pointer]:
          - link "Hana Users" [ref=e39]:
            - /url: https://www.facebook.com/groups/845049833221837/
            - generic [ref=e41]: Hana Users
      - list [ref=e43]:
        - listitem [ref=e44] [cursor=pointer]:
          - link " Punch Clock" [ref=e45]:
            - /url: /Dashboard/punch_clock
            - generic [ref=e46]: 
            - generic [ref=e47]: Punch Clock
    - generic [ref=e48]:
      - navigation [ref=e50]:
        - generic [ref=e51]:
          - generic [ref=e52]:
            - text:   
            - link " 1" [ref=e53] [cursor=pointer]:
              - /url: javascript:void(0);
              - generic [ref=e54]: 
              - generic [ref=e56]: "1"
            - link " 36" [ref=e57] [cursor=pointer]:
              - /url: javascript:void(0);
              - generic [ref=e58]: 
              - generic [ref=e60]: "36"
            - text: 
          - text: 
        - generic [ref=e61]:
          - list [ref=e62]:
            - listitem [ref=e63]:
              - button "New Order" [expanded] [ref=e66] [cursor=pointer]:
                - generic [ref=e67]: 
                - text: New Order
            - listitem [ref=e69]:
              - button "Dispatch" [expanded] [ref=e72] [cursor=pointer]:
                - generic [ref=e73]: 
                - text: Dispatch
            - listitem [ref=e75]:
              - button [expanded] [ref=e76] [cursor=pointer]:
                - generic [ref=e77]: 
          - list [ref=e78]:
            - listitem
            - listitem [ref=e79]:
              - generic [ref=e80]:
                - generic: 
                - textbox "Search for any order..." [ref=e81]
            - listitem [ref=e82]:
              - link "" [ref=e83] [cursor=pointer]:
                - /url: javascript:void(0);
                - generic [ref=e84]: 
            - listitem [ref=e85]:
              - generic [ref=e87]:
                - button "Notifications" [ref=e89] [cursor=pointer]:
                  - img [ref=e91]
                  - generic [ref=e94]: "30"
                - text:                                 
            - listitem [ref=e95]:
              - button [ref=e96] [cursor=pointer]:
                - generic [ref=e97]: 
              - text:    
            - listitem [ref=e98]:
              - button [expanded] [ref=e99] [cursor=pointer]:
                - generic [ref=e100]: 
            - listitem [ref=e101]:
              - button [expanded] [ref=e102] [cursor=pointer]:
                - img [ref=e103]
            - listitem [ref=e104]:
              - button "" [ref=e105] [cursor=pointer]:
                - generic [ref=e106]: 
              - text:      
      - generic [ref=e107]:
        - generic [ref=e111]:
          - generic [ref=e113]:
            - generic [ref=e114]: Shop
            - combobox [disabled] [ref=e115]:
              - option "--Select Shop--"
              - option "Automation Shop" [selected]
              - option "Canada Shop Automation"
              - option "Manual hanapos (Canada)"
              - option "sisterchicks flowers and gifts"
          - generic [ref=e117]:
            - link "Add Proposal" [ref=e119] [cursor=pointer]:
              - /url: javascript:void(0)
              - generic [ref=e120]: 
              - text: Add Proposal
            - link "View Proposals" [ref=e122] [cursor=pointer]:
              - /url: /Proposal/Index
            - link "View Packages" [ref=e124] [cursor=pointer]:
              - /url: /Proposal/ViewPackages
          - link [ref=e127] [cursor=pointer]:
            - /url: /Proposal/ProposalSetting
            - generic [ref=e128]: 
        - text:   
        - generic [ref=e131]:
          - generic [ref=e132]:
            - generic [ref=e133]:
              - generic [ref=e135]:
                - link [ref=e137] [cursor=pointer]:
                  - /url: /Proposal/Index
                  - generic [ref=e138]: 
                - text: 
                - generic [ref=e139]: Add Proposal
                - generic [ref=e141] [cursor=pointer]: Missing Info
              - generic [ref=e142]:
                - generic [ref=e144]:
                  - text: "Bride:"
                  - generic [ref=e145]: Abish David
                - generic [ref=e147]:
                  - text: "Groom:"
                  - generic [ref=e148]: Demarco Oberbrunner-Hilpert
                - generic [ref=e150]:
                  - text: "Phone:"
                  - generic [ref=e151]: "9566550756"
                - generic [ref=e153]:
                  - text: "Location:"
                  - generic [ref=e154]: 808 Amira Course
                - generic [ref=e156]:
                  - text: "Date:"
                  - generic [ref=e157]: 05/20/2026
                - generic [ref=e159]:
                  - text: "Created on:"
                  - generic [ref=e160]: Apr 30, 2026 04:44AM
                - generic [ref=e162]:
                  - generic [ref=e163]: "Total:"
                  - generic [ref=e164]: $16.18
            - generic [ref=e165]:
              - generic [ref=e166]:
                - generic [ref=e167]:
                  - generic [ref=e168]: "Proposal ID:"
                  - generic [ref=e169]: "240532"
                - generic [ref=e171]: "Proposal type:"
                - combobox [disabled] [ref=e173]:
                  - option "Event"
                  - option "Wedding" [selected]
                - combobox [ref=e175]:
                  - option "References" [selected]
                  - option "QA Wedding Automation"
              - generic [ref=e176]:
                - generic [ref=e178] [cursor=pointer]:
                  - generic [ref=e179]: 
                  - text: Overview
                - generic [ref=e180]:
                  - generic [ref=e181]: 
                  - link "Florist View" [ref=e182] [cursor=pointer]:
                    - /url: javascript:void(0)
                - generic [ref=e183]:
                  - generic [ref=e184]: 
                  - link "E-mail Conversation" [ref=e185] [cursor=pointer]:
                    - /url: javascript:void(0)
                - generic [ref=e186]:
                  - generic [ref=e187]: 
                  - link "Print" [ref=e188] [cursor=pointer]:
                    - /url: javascript:void(0)
                - generic [ref=e192]:
                  - link "" [ref=e193] [cursor=pointer]:
                    - /url: ""
                    - generic [ref=e194]: 
                  - text:  
            - text: 
          - generic [ref=e195]:
            - generic [ref=e196]:
              - list [ref=e198]:
                - listitem [ref=e199]:
                  - link "Couple Info" [ref=e200] [cursor=pointer]:
                    - /url: "#divCoupleInfo"
                - listitem [ref=e201]:
                  - link "Documents and images" [expanded] [ref=e202] [cursor=pointer]:
                    - /url: "#divDocumentImages"
                - listitem [ref=e203]:
                  - link "Inspiration board" [ref=e204] [cursor=pointer]:
                    - /url: "#divInspirationBoard"
                - listitem [ref=e205]:
                  - link "Items & products" [ref=e206] [cursor=pointer]:
                    - /url: "#divItemsProducts"
                - listitem [ref=e207]:
                  - link "Notes and instructions" [ref=e208] [cursor=pointer]:
                    - /url: "#divNotes"
                - listitem [ref=e209]:
                  - link "Timeline" [ref=e210] [cursor=pointer]:
                    - /url: "#divTimeline"
                - listitem [ref=e211]:
                  - link "Contract" [ref=e212] [cursor=pointer]:
                    - /url: "#divContractSummary"
                - listitem
              - generic [ref=e213]:
                - text:         
                - generic [ref=e214]:
                  - list [ref=e216]:
                    - listitem [ref=e217]:
                      - link "Upload images" [expanded] [active] [ref=e218] [cursor=pointer]:
                        - /url: "#divUploadImages"
                    - listitem [ref=e219]:
                      - link "Upload documents" [expanded] [ref=e220] [cursor=pointer]:
                        - /url: "#divUploadDocuments"
                  - generic [ref=e221]:
                    - generic [ref=e226]:
                      - paragraph [ref=e227]: For best rendering of proposals for your clients, upload images in "multiples of 3".
                      - paragraph [ref=e229]: Page 1 Your event / wedding images to illustrate the theme, look and feel. Max image size 5MB.
                      - generic [ref=e231]:
                        - button "" [ref=e234] [cursor=pointer]:
                          - generic [ref=e235]: 
                        - generic [ref=e236]:
                          - generic [ref=e237]: Image 1
                          - generic [ref=e238]: "Min size: (236 * 360)"
                      - generic [ref=e240]:
                        - text: 
                        - generic [ref=e243]:
                          - generic [ref=e244]: Image 2
                          - generic [ref=e245]: "Min size: (236 * 360)"
                      - generic [ref=e247]:
                        - text: 
                        - generic [ref=e250]:
                          - generic [ref=e251]: Image 3
                          - generic [ref=e252]: "Min size: (333 * 724)"
                      - paragraph [ref=e254]: Page 2 Your event / wedding images to illustrate the theme, look and feel. Max image size 5MB.
                      - generic [ref=e256]:
                        - text: 
                        - generic [ref=e259]:
                          - generic [ref=e260]: Image 1
                          - generic [ref=e261]: "Min size: (330 * 292)"
                      - generic [ref=e263]:
                        - text: 
                        - generic [ref=e266]:
                          - generic [ref=e267]: Image 2
                          - generic [ref=e268]: "Min size: (160 * 132)"
                      - generic [ref=e270]:
                        - text: 
                        - generic [ref=e273]:
                          - generic [ref=e274]: Image 3
                          - generic [ref=e275]: "Min size: (160 * 132)"
                      - generic [ref=e277]:
                        - text: 
                        - generic [ref=e280]:
                          - generic [ref=e281]: Image 4
                          - generic [ref=e282]: "Min size: (198 * 274)"
                      - generic [ref=e284]:
                        - text: 
                        - generic [ref=e287]:
                          - generic [ref=e288]: Image 5
                          - generic [ref=e289]: "Min size: (57 * 132)"
                      - generic [ref=e291]:
                        - text: 
                        - generic [ref=e294]:
                          - generic [ref=e295]: Image 6
                          - generic [ref=e296]: "Min size: (57 * 132)"
                      - generic [ref=e298]:
                        - text: 
                        - generic [ref=e301]:
                          - generic [ref=e302]: Image 7
                          - generic [ref=e303]: "Min size: (57 * 132)"
                      - generic [ref=e305]:
                        - text: 
                        - generic [ref=e308]:
                          - generic [ref=e309]: Image 8
                          - generic [ref=e310]: "Min size: (57 * 132)"
                      - generic [ref=e312]:
                        - text: 
                        - generic [ref=e315]:
                          - generic [ref=e316]: Image 9
                          - generic [ref=e317]: "Min size: (57 * 132)"
                      - generic [ref=e319]:
                        - text: 
                        - generic [ref=e322]:
                          - generic [ref=e323]: Image 10
                          - generic [ref=e324]: "Min size: (57 * 132)"
                      - generic [ref=e326]:
                        - text: 
                        - generic [ref=e329]:
                          - generic [ref=e330]: Image 11
                          - generic [ref=e331]: "Min size: (189 * 292)"
                      - generic [ref=e333]:
                        - text: 
                        - generic [ref=e336]:
                          - generic [ref=e337]: Image 12
                          - generic [ref=e338]: "Min size: (132 * 113)"
                      - generic [ref=e340]:
                        - text: 
                        - generic [ref=e343]:
                          - generic [ref=e344]: Image 13
                          - generic [ref=e345]: "Min size: (132 * 170)"
                      - generic [ref=e347]:
                        - text: 
                        - generic [ref=e350]:
                          - generic [ref=e351]: Image 14
                          - generic [ref=e352]: "Min size: (293 * 160)"
                      - generic [ref=e354]:
                        - text: 
                        - generic [ref=e357]:
                          - generic [ref=e358]: Image 15
                          - generic [ref=e359]: "Min size: (160 * 245)"
                      - generic [ref=e361]:
                        - text: 
                        - generic [ref=e364]:
                          - generic [ref=e365]: Image 16
                          - generic [ref=e366]: "Min size: (123 * 245)"
                    - text: 
                - text:                               
            - text: 
        - text: 
        - text:   OFF  OFF  OFF 
        - generic:    OFF OFF OFF OFF   OFF
        - text:     
  - generic [ref=e368]:
    - generic [ref=e369]:
      - strong [ref=e370]: Copyright
      - text: Hana © 2026
    - list [ref=e372]:
      - list [ref=e376]:
        - listitem [ref=e377]:
          - generic [ref=e378]: 
          - link "Big news for florists - Hana Accounting is officially here" [ref=e379] [cursor=pointer]:
            - /url: /Account/ViewNews?id=250
    - text: 
  - text:      
  - status [ref=e380]
  - text:                 OFF               OFF           
  - generic: 
  - text:        OFF  OFF  OFF  OFF  OFF  OFF  OFF  OFF    OFF OFF  OFF OFF  OFF  OFF  OFF OFF  OFF OFF  OFF  OFF      
  - iframe [ref=e381]:
    
  - status [ref=e382]
  - status [ref=e383]
  - status [ref=e384]
  - iframe [ref=e386]:
    - button "Open chat" [ref=f54e1] [cursor=pointer]
  - text:  
```

# Test source

```ts
  2082 |       );
  2083 |     }
  2084 |   }
  2085 | 
  2086 |   /**
  2087 |    * Verifies Wedding Coordinator Address on the page.
  2088 |    * @param address - Address value used for this action.
  2089 |    */
  2090 |   async verifyWeddingCoordinatorAddress(address: string) {
  2091 |     try {
  2092 |       await this.verifyValue(
  2093 |         this.weddingCoordinatorAddress,
  2094 |         address,
  2095 |         "Wedding Coordinator Address textbox"
  2096 |       );
  2097 |     } catch (error) {
  2098 |       throw new Error(
  2099 |         `Failed to verify Wedding Coordinator Address. Reason: ${error}`
  2100 |       );
  2101 |     }
  2102 |   }
  2103 | 
  2104 |   /**
  2105 |    * Sets Wedding Coordinator Zip on the page.
  2106 |    * @param zip - Input value used by this operation.
  2107 |    */
  2108 |   async setWeddingCoordinatorZip(zip: string) {
  2109 |     try {
  2110 |       await this.clickAndType(
  2111 |         this.weddingCoordinatorZip,
  2112 |         zip,
  2113 |         "Wedding Coordinator Zip textbox"
  2114 |       );
  2115 |     } catch (error) {
  2116 |       throw new Error(
  2117 |         `Failed to set Wedding Coordinator Zip. Reason: ${error}`
  2118 |       );
  2119 |     }
  2120 |   }
  2121 | 
  2122 |   /**
  2123 |    * Verifies Wedding Coordinator Zip on the page.
  2124 |    * @param zip - Input value used by this operation.
  2125 |    */
  2126 |   async verifyWeddingCoordinatorZip(zip: string) {
  2127 |     try {
  2128 |       await this.verifyValue(
  2129 |         this.weddingCoordinatorZip,
  2130 |         zip,
  2131 |         "Wedding Coordinator Zip textbox"
  2132 |       );
  2133 |     } catch (error) {
  2134 |       throw new Error(
  2135 |         `Failed to verify Wedding Coordinator Zip. Reason: ${error}`
  2136 |       );
  2137 |     }
  2138 |   }
  2139 | 
  2140 |   /**
  2141 |    * Clicks Document Images Tab on the page.
  2142 |    */
  2143 |   async clickDocumentImagesTab() {
  2144 |     try {
  2145 |       await this.documentImagesTab.waitFor({ state: "visible" });
  2146 |       await this.documentImagesTab.dispatchEvent("click");
  2147 |     } catch (error) {
  2148 |       throw new Error(`Failed to click Document Images Tab. Reason: ${error}`);
  2149 |     }
  2150 |   }
  2151 | 
  2152 |   /**
  2153 |    * Clicks Upload Images Tab on the page.
  2154 |    */
  2155 |   async clickUploadImagesTab() {
  2156 |     try {
  2157 |       await this.clickElement(
  2158 |         this.page,
  2159 |         this.uploadimagestab,
  2160 |         "Upload Images Tab"
  2161 |       );
  2162 |     } catch (error) {
  2163 |       throw new Error(`Failed to click Upload Images Tab. Reason: ${error}`);
  2164 |     }
  2165 |   }
  2166 | 
  2167 |   /**
  2168 |    * Performs Upload Image1 on the page.
  2169 |    * @param filePath - Input value used by this operation.
  2170 |    */
  2171 |   async uploadImage1(filePath: string) {
  2172 |     try {
  2173 |       await this.hoverOnElement(this.uploadimagestabimage1, "Image 1 Label");
  2174 |       const [fileChooser] = await Promise.all([
  2175 |         this.page.waitForEvent("filechooser"),
  2176 |         this.uploadimagestabimage1uploadbtn.dispatchEvent("click"),
  2177 |       ]);
  2178 |       await fileChooser.setFiles(filePath);
  2179 |       await this.page.waitForTimeout(2000);
  2180 |       console.log("Image 1 uploaded successfully.");
  2181 |     } catch (error) {
> 2182 |       throw new Error(`Failed to upload Image 1. Reason: ${error}`);
       |             ^ Error: Failed to upload Image 1. Reason: Error: ENOENT: no such file or directory, stat 'testFiles\roses red.jpg'
  2183 |     }
  2184 |   }
  2185 | 
  2186 |   /**
  2187 |    * Performs Upload Image2 on the page.
  2188 |    * @param filePath - Input value used by this operation.
  2189 |    */
  2190 |   async uploadImage2(filePath: string) {
  2191 |     try {
  2192 |       await this.hoverOnElement(this.uploadimagestabimage2, "Image 2 Label");
  2193 |       const [fileChooser] = await Promise.all([
  2194 |         this.page.waitForEvent("filechooser"),
  2195 |         this.uploadimagestabimage2uploadbtn.dispatchEvent("click"),
  2196 |       ]);
  2197 |       await fileChooser.setFiles(filePath);
  2198 |       await this.page.waitForTimeout(2000);
  2199 |       console.log("Image 2 uploaded successfully.");
  2200 |     } catch (error) {
  2201 |       throw new Error(`Failed to upload Image 2. Reason: ${error}`);
  2202 |     }
  2203 |   }
  2204 | 
  2205 |   /**
  2206 |    * Performs Upload Image3 on the page.
  2207 |    * @param filePath - Input value used by this operation.
  2208 |    */
  2209 |   async uploadImage3(filePath: string) {
  2210 |     try {
  2211 |       await this.hoverOnElement(this.uploadimagestabimage3, "Image 3 Label");
  2212 |       const [fileChooser] = await Promise.all([
  2213 |         this.page.waitForEvent("filechooser"),
  2214 |         this.uploadimagestabimage3uploadbtn.dispatchEvent("click"),
  2215 |       ]);
  2216 |       await fileChooser.setFiles(filePath);
  2217 |       await this.page.waitForTimeout(2000);
  2218 |       console.log("Image 3 uploaded successfully.");
  2219 |     } catch (error) {
  2220 |       throw new Error(`Failed to upload Image 3. Reason: ${error}`);
  2221 |     }
  2222 |   }
  2223 | 
  2224 |   /**
  2225 |    * Clicks On Upload Documents Tab on the page.
  2226 |    */
  2227 |   async clickOnUploadDocumentsTab() {
  2228 |     await this.clickElement(
  2229 |       this.page,
  2230 |       this.uploaddocumentstab,
  2231 |       "Upload Documents Tab"
  2232 |     );
  2233 |     await this.uploaddocumentstab.waitFor({ state: "visible" });
  2234 |   }
  2235 | 
  2236 |   // Header actions and popups
  2237 |   /**
  2238 |    * Clicks Florist View Link And Wait For New Page on the page.
  2239 |    * @returns Returns Promise<Page>.
  2240 |    */
  2241 |   async clickFloristViewLinkAndWaitForNewPage(): Promise<Page> {
  2242 |     const [newPage] = await Promise.all([
  2243 |       this.page.context().waitForEvent("page"),
  2244 |       this.clickElement(this.page, this.floristViewLink, "Florist View Link"),
  2245 |     ]);
  2246 |     await newPage.waitForLoadState("domcontentloaded");
  2247 |     return newPage;
  2248 |   }
  2249 | 
  2250 |   /**
  2251 |    * Gets Florist View Title Text on the page.
  2252 |    * @returns Returns the extracted value as a string.
  2253 |    */
  2254 |   async getFloristViewTitleText(): Promise<string> {
  2255 |     return await this.getTextContent(this.floristViewTitle);
  2256 |   }
  2257 | 
  2258 |   /**
  2259 |    * Checks whether Florist Wedding Info Header Displayed is available or valid on the page.
  2260 |    * @returns Returns true when the target condition is satisfied; otherwise false.
  2261 |    */
  2262 |   async isFloristWeddingInfoHeaderDisplayed(): Promise<boolean> {
  2263 |     return await this.floristWeddingInfoHeader.isVisible();
  2264 |   }
  2265 | 
  2266 |   /**
  2267 |    * Checks whether Florist Event Info Header Displayed is available or valid on the page.
  2268 |    * @returns Returns true when the target condition is satisfied; otherwise false.
  2269 |    */
  2270 |   async isFloristEventInfoHeaderDisplayed(): Promise<boolean> {
  2271 |     return await this.floristEventInfoHeader.isVisible();
  2272 |   }
  2273 | 
  2274 |   /**
  2275 |    * Checks whether Florist Coordinator Info Header Displayed is available or valid on the page.
  2276 |    * @returns Returns true when the target condition is satisfied; otherwise false.
  2277 |    */
  2278 |   async isFloristCoordinatorInfoHeaderDisplayed(): Promise<boolean> {
  2279 |     return await this.floristCoordinatorInfoHeader.isVisible();
  2280 |   }
  2281 | 
  2282 |   /**
```