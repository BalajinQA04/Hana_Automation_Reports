# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: customerPortalPaymentTestcases/Hana_T_CustomerPortalPaymentWithExistingCustomer.spec.ts >> Hana_T Customer Portal Payment with Existing Customer Functionality Test
- Location: tests/customerPortalPaymentTestcases/Hana_T_CustomerPortalPaymentWithExistingCustomer.spec.ts:67:1

# Error details

```
Error: ❌ TEXT VERIFICATION FAILED
Field Name : Toast message text
Expected   : "Successfully paid amount"
Actual     : "The provided key 'rk_live_*********************************************************************************************92DiNl' does not have access to account 'acct_1JfiLzPwVHWMhtrH' (or that account does not exist). Application access may have been revoked."
Mode       : playwright-normalized | exact
Reason     : expect(locator).toHaveText(expected) failed

Locator:  locator('div.toast-message')
Expected: "Successfully paid amount"
Received: "The provided key 'rk_live_*********************************************************************************************92DiNl' does not have access to account 'acct_1JfiLzPwVHWMhtrH' (or that account does not exist). Application access may have been revoked."
Timeout:  10000ms

Call log:
  - Expect "toHaveText" with timeout 10000ms
  - waiting for locator('div.toast-message')
    14 × locator resolved to <div class="toast-message">The provided key 'rk_live_***********************…</div>
       - unexpected value "The provided key 'rk_live_*********************************************************************************************92DiNl' does not have access to account 'acct_1JfiLzPwVHWMhtrH' (or that account does not exist). Application access may have been revoked."

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
        - generic [ref=e109]:
          - heading "Customer" [level=2] [ref=e112]
          - generic [ref=e115]:
            - generic [ref=e116]: Shop
            - combobox [ref=e117]:
              - option "All"
              - option "Automation Shop" [selected]
              - option "Canada Shop Automation"
              - option "Manual hanapos (Canada)"
              - option "sisterchicks flowers and gifts"
          - generic [ref=e120]:
            - generic [ref=e121]:
              - generic [ref=e122]:
                - button "New Customer" [ref=e123] [cursor=pointer]
                - button "Merge Customer" [disabled] [ref=e124]
                - button "Email Invoices" [disabled] [ref=e125]
                - button "Print Invoices" [disabled] [ref=e126]
                - button "Generate Statements" [ref=e127] [cursor=pointer]
              - generic [ref=e128]:
                - text: 
                - generic [ref=e129]:
                  - text: Only With Balance
                  - generic [ref=e130]: 
                - generic [ref=e131] [cursor=pointer]: "OFF"
            - generic [ref=e134]:
              - grid [ref=e137]:
                - rowgroup [ref=e154]:
                  - row "Action Customer Id Customer Name Company Name Phone Number Alt Phone Number Address City State Zip / Postal Code Account Balance Store Credit 0-30 31-60 61-90 90+" [ref=e155]:
                    - columnheader [ref=e156]:
                      - checkbox [ref=e157] [cursor=pointer]
                    - columnheader "Action" [ref=e158]
                    - columnheader "Customer Id" [ref=e159]:
                      - link "Customer Id" [ref=e160] [cursor=pointer]:
                        - /url: "#"
                    - columnheader "Customer Name" [ref=e161]:
                      - link "Customer Name" [ref=e162] [cursor=pointer]:
                        - /url: "#"
                    - columnheader "Company Name" [ref=e163]:
                      - link "Company Name" [ref=e164] [cursor=pointer]:
                        - /url: "#"
                    - columnheader "Phone Number" [ref=e165]:
                      - link "Phone Number" [ref=e166] [cursor=pointer]:
                        - /url: "#"
                    - columnheader "Alt Phone Number" [ref=e167]:
                      - link "Alt Phone Number" [ref=e168] [cursor=pointer]:
                        - /url: "#"
                    - columnheader "Address" [ref=e169]:
                      - link "Address" [ref=e170] [cursor=pointer]:
                        - /url: "#"
                    - columnheader "City State Zip / Postal Code" [ref=e171]:
                      - link "City State Zip / Postal Code" [ref=e172] [cursor=pointer]:
                        - /url: "#"
                    - columnheader "Account Balance" [ref=e173]:
                      - link "Account Balance" [ref=e174] [cursor=pointer]:
                        - /url: "#"
                    - columnheader "Store Credit" [ref=e175]:
                      - link "Store Credit" [ref=e176] [cursor=pointer]:
                        - /url: "#"
                    - columnheader "0-30" [ref=e177]:
                      - link "0-30" [ref=e178] [cursor=pointer]:
                        - /url: "#"
                    - columnheader "31-60" [ref=e179]:
                      - link "31-60" [ref=e180] [cursor=pointer]:
                        - /url: "#"
                    - columnheader "61-90" [ref=e181]:
                      - link "61-90" [ref=e182] [cursor=pointer]:
                        - /url: "#"
                    - columnheader "90+" [ref=e183]:
                      - link "90+" [ref=e184] [cursor=pointer]:
                        - /url: "#"
                  - row "Abish David " [ref=e185]:
                    - columnheader [ref=e186]
                    - columnheader [ref=e187]
                    - text:   
                    - columnheader [ref=e188]:
                      - generic [ref=e190]:
                        - generic [ref=e191]:
                          - textbox [ref=e192]
                          - text: 
                        - text: 
                    - columnheader "Abish David " [ref=e193]:
                      - generic [ref=e195]:
                        - generic [ref=e196]:
                          - textbox [ref=e197]: Abish David
                          - text: 
                        - button "" [ref=e198] [cursor=pointer]:
                          - generic [ref=e199]: 
                    - columnheader [ref=e200]:
                      - generic [ref=e202]:
                        - generic [ref=e203]:
                          - textbox [ref=e204]
                          - text: 
                        - text: 
                    - columnheader [ref=e205]:
                      - generic [ref=e207]:
                        - generic [ref=e208]:
                          - textbox [ref=e209]
                          - text: 
                        - text: 
                    - columnheader [ref=e210]:
                      - generic [ref=e212]:
                        - generic [ref=e213]:
                          - textbox [ref=e214]
                          - text: 
                        - text: 
                    - columnheader [ref=e215]:
                      - generic [ref=e217]:
                        - generic [ref=e218]:
                          - textbox [ref=e219]
                          - text: 
                        - text: 
                    - columnheader [ref=e220]:
                      - generic [ref=e222]:
                        - generic [ref=e223]:
                          - textbox [ref=e224]
                          - text: 
                        - text: 
                    - columnheader [ref=e225]
                    - columnheader [ref=e226]
                    - columnheader [ref=e227]
                    - columnheader [ref=e228]
                    - columnheader [ref=e229]
                    - columnheader [ref=e230]
                    - text:  
              - grid [ref=e232]:
                - rowgroup [ref=e249]:
                  - row "  15047561 Abish David Hana_Sisterchicks 956-655-0756 956-655-0756 3402 Park Blvd San Diego CA 92103 $2,288,393.75 $0.00 $252,516.97 $0.00 $0.00 $2,035,876.78" [ref=e250]:
                    - gridcell [ref=e251]:
                      - checkbox [ref=e252] [cursor=pointer]
                    - gridcell " " [ref=e253]:
                      - generic [ref=e254]:
                        - generic [ref=e257]:
                          - link "" [ref=e258] [cursor=pointer]:
                            - /url: ""
                            - generic [ref=e259]: 
                          - text:       
                        - link "" [ref=e262] [cursor=pointer]:
                          - /url: javascript:void(0);
                          - generic [ref=e263]: 
                    - gridcell "15047561" [ref=e264]
                    - gridcell "Abish David" [ref=e265]
                    - gridcell "Hana_Sisterchicks" [ref=e266]
                    - gridcell "956-655-0756" [ref=e267]:
                      - img [ref=e269]
                      - link "956-655-0756" [ref=e270] [cursor=pointer]:
                        - /url: tel:9566550756
                    - gridcell "956-655-0756" [ref=e271]:
                      - img [ref=e273]
                      - link "956-655-0756" [ref=e274] [cursor=pointer]:
                        - /url: tel:9566550756
                    - gridcell "3402 Park Blvd" [ref=e275]
                    - gridcell "San Diego CA 92103" [ref=e276]
                    - gridcell "$2,288,393.75" [ref=e277]
                    - gridcell "$0.00" [ref=e278]
                    - gridcell "$252,516.97" [ref=e279]
                    - gridcell "$0.00" [ref=e280]
                    - gridcell "$0.00" [ref=e281]
                    - gridcell "$2,035,876.78" [ref=e282]
              - generic [ref=e283]:
                - link "Go to the first page" [ref=e284]:
                  - /url: "#"
                  - generic [ref=e285]: 
                - link "Go to the previous page" [ref=e286]:
                  - /url: "#"
                  - generic [ref=e287]: 
                - list [ref=e288]:
                  - listitem [ref=e289]:
                    - generic [ref=e290] [cursor=pointer]: "1"
                - link "Go to the next page" [ref=e291]:
                  - /url: "#"
                  - generic [ref=e292]: 
                - link "Go to the last page" [ref=e293]:
                  - /url: "#"
                  - generic [ref=e294]: 
                - listbox [ref=e296] [cursor=pointer]:
                  - generic [ref=e297]:
                    - generic [ref=e298]: "25"
                    - generic "select" [ref=e299]:
                      - generic [ref=e300]: 
                - link "" [ref=e301] [cursor=pointer]:
                  - /url: "#"
                  - generic [ref=e302]: 
                - generic [ref=e303]: 1 - 1 of 1 items
        - text:  OFF  OFF  OFF  ON  OFF OFF  OFF  OFF    
  - generic [ref=e304]:
    - generic [ref=e305]:
      - strong [ref=e306]: Copyright
      - text: Hana © 2026
    - list [ref=e308]:
      - list [ref=e312]:
        - listitem [ref=e313]:
          - generic [ref=e314]: 
          - link "Big news for florists - Hana Accounting is officially here" [ref=e315] [cursor=pointer]:
            - /url: /Account/ViewNews?id=250
    - text: 
  - text:       ; ; ;
  - status [ref=e316]
  - text:                 OFF               OFF           
  - generic: 
  - text:        OFF  OFF  OFF  OFF  OFF  OFF  OFF  OFF
  - dialog [ref=e317]:
    - generic [ref=e319]:
      - generic [ref=e320]:
        - generic [ref=e321] [cursor=pointer]: 
        - heading [level=4] [ref=e322]: Customer Details
        - generic [ref=e324]:
          - text: Abish David (15047561)
          - generic [ref=e325]: 
          - text: 956-655-0756 Hana_Sisterchicks
        - generic [ref=e327]: Please note, this House Account is past due by 238 days. $2035876.78 past due.
      - generic [ref=e329]:
        - list [ref=e330]:
          - listitem [ref=e331]:
            - link [ref=e332] [cursor=pointer]:
              - /url: "#tab-CutomerDtl"
              - text: Profile
          - listitem [ref=e333]:
            - link [expanded] [ref=e334] [cursor=pointer]:
              - /url: "#tab-CutomerProtalLoginDtl"
              - text: Portal Login
          - listitem [ref=e335]:
            - link [ref=e336] [cursor=pointer]:
              - /url: "#tab-CutomerBLDtl"
              - text: Billing Address
          - listitem [ref=e337]:
            - link [ref=e338] [cursor=pointer]:
              - /url: "#tab-CutomerCCDtl"
              - text: Credit Card
          - listitem [ref=e339]:
            - link [ref=e340] [cursor=pointer]:
              - /url: "#tab-CutomerDefaultDtl"
              - text: Preferences
          - listitem [ref=e341]:
            - link [ref=e342] [cursor=pointer]:
              - /url: "#tab-CutomerUnpaidInvoiceDtl"
              - text: UnPaid Invoice(s)
          - listitem [ref=e343]:
            - link [ref=e344] [cursor=pointer]:
              - /url: "#tab-CutomerPaymentDtl"
              - text: Payment Detail(s)
          - listitem [ref=e345]:
            - link [ref=e346] [cursor=pointer]:
              - /url: "#tab-CutomerOrderDtl"
              - text: Order Detail(s)
          - listitem [ref=e347]:
            - link [ref=e348] [cursor=pointer]:
              - /url: "#tab-GenerateStatementDtl"
              - text: Statement(s)
        - generic [ref=e349]:
          - text:    ON   ON   ON   ON   ON   ON   ON  OFF
          - generic [ref=e351]:
            - generic [ref=e353]:
              - generic [ref=e354]: User ID
              - textbox [disabled] [ref=e355]: "15047561"
            - generic [ref=e357]:
              - generic [ref=e358]: Password
              - textbox [ref=e359]: Test@123
            - generic [ref=e361]:
              - generic [ref=e363]:
                - generic [ref=e364]: Referral URL
                - textbox [active] [ref=e365] [cursor=pointer]: https://automationshop.hanawebsites.com/?id=MTUwNDc1NjE=
                - text: "Note: Referral URL tracking works ONLY if you are using Hana hosted website."
              - button [ref=e368] [cursor=pointer]:
                - generic [ref=e369]: 
              - link [ref=e372] [cursor=pointer]:
                - /url: https://hanafloralpos3.com/CustomerPortal/Login?ShopID=2061&CustomerID=15047561
                - text: Customer portal login
            - generic [ref=e373]:
              - button [ref=e374] [cursor=pointer]: Send credential e-mail
              - button [ref=e375] [cursor=pointer]: Save
          - text: 
  - text:    
  - iframe [ref=e376]:
    
  - iframe [ref=e378]:
    - button "Open chat" [ref=f101e1] [cursor=pointer]
```

# Test source

```ts
  1048 |         `Attempts   : ${attempts} (each ${timeoutPerAttemptMs / 1000}s)\n` +
  1049 |         `Max Wait   : ${totalTimeoutMs / 1000}s\n` +
  1050 |         `URL        : ${this.page.url()}\n` +
  1051 |         `ReadyState : ${readyState}\n` +
  1052 |         `Matches    : ${locatorCount}\n` +
  1053 |         `Visible    : ${isVisible}\n` +
  1054 |         `Error Type : ${errorType}\n` +
  1055 |         `Details    : ${errorMessage}`,
  1056 |     );
  1057 |   }
  1058 | 
  1059 |   async verifyVisibilitySoft(locator: Locator, fieldName: string) {
  1060 |     await locator.waitFor({ state: "attached" });
  1061 |     await locator.waitFor({ state: "visible" });
  1062 |     // await this.highlight(locator);
  1063 |     await expect.soft(locator, `${fieldName} should be visible`).toBeVisible();
  1064 |   }
  1065 | 
  1066 |   async verifyTextSoft(locator: Locator, expected: string, fieldName: string) {
  1067 |     await locator.waitFor({ state: "attached" });
  1068 |     await locator.waitFor({ state: "visible" });
  1069 |     await expect
  1070 |       .soft(
  1071 |         locator,
  1072 |         `Expected Value should be matched with actual value for the field ${fieldName}`,
  1073 |       )
  1074 |       .toHaveText(expected);
  1075 |   }
  1076 | 
  1077 |   async verifyText(
  1078 |     locator: Locator,
  1079 |     expected: string,
  1080 |     fieldName: string,
  1081 |     options: {
  1082 |       exact?: boolean;
  1083 |       timeout?: number;
  1084 |       normalize?: boolean;
  1085 |       raw?: boolean;
  1086 |       ignoreWhitespace?: boolean;
  1087 |     } = {},
  1088 |   ) {
  1089 |     const {
  1090 |       exact = true,
  1091 |       timeout = 10000,
  1092 |       normalize = true,
  1093 |       raw = false,
  1094 |       ignoreWhitespace = false,
  1095 |     } = options;
  1096 | 
  1097 |     const normalizeText = (text: string) => text.trim().replace(/\s+/g, " ");
  1098 |     const stripWhitespace = (text: string) => text.replace(/\s+/g, "");
  1099 |     const expectedValue = normalize ? normalizeText(expected) : expected;
  1100 | 
  1101 |     if (!fieldName?.trim()) {
  1102 |       throw new Error(`❌ verifyText: fieldName is required`);
  1103 |     }
  1104 | 
  1105 |     try {
  1106 |       if (ignoreWhitespace) {
  1107 |         await expect(locator).toBeVisible({ timeout });
  1108 |         const actualForCompare = (await locator.innerText()) ?? "";
  1109 |         const expectedCompare = stripWhitespace(expectedValue);
  1110 |         const actualCompare = stripWhitespace(actualForCompare);
  1111 | 
  1112 |         if (exact) {
  1113 |           expect(actualCompare).toBe(expectedCompare);
  1114 |         } else {
  1115 |           expect(actualCompare).toContain(expectedCompare);
  1116 |         }
  1117 | 
  1118 |         return;
  1119 |       }
  1120 | 
  1121 |       if (raw) {
  1122 |         const actualRaw = (await locator.textContent()) ?? "";
  1123 | 
  1124 |         if (exact) {
  1125 |           expect(actualRaw).toBe(expectedValue);
  1126 |         } else {
  1127 |           expect(actualRaw).toContain(expectedValue);
  1128 |         }
  1129 | 
  1130 |         return;
  1131 |       }
  1132 | 
  1133 |       if (exact) {
  1134 |         await expect(locator).toHaveText(expectedValue, {
  1135 |           timeout,
  1136 |         });
  1137 |       } else {
  1138 |         await expect(locator).toContainText(expectedValue, {
  1139 |           timeout,
  1140 |         });
  1141 |       }
  1142 | 
  1143 |     } catch (error: any) {
  1144 |       const actual = raw
  1145 |         ? ((await locator.textContent().catch(() => "")) || "")
  1146 |         : ((await locator.innerText().catch(() => "")) || "");
  1147 | 
> 1148 |       throw new Error(
       |             ^ Error: ❌ TEXT VERIFICATION FAILED
  1149 |         `❌ TEXT VERIFICATION FAILED\n` +
  1150 |           `Field Name : ${fieldName}\n` +
  1151 |           `Expected   : "${expected}"\n` +
  1152 |           `Actual     : "${actual.trim() || "EMPTY"}"\n` +
  1153 |           `Mode       : ${
  1154 |             ignoreWhitespace
  1155 |               ? "ignore-whitespace"
  1156 |               : raw
  1157 |                 ? "raw"
  1158 |                 : "playwright-normalized"
  1159 |           } | ${exact ? "exact" : "contains"}\n` +
  1160 |           `Reason     : ${error.message}`,
  1161 |       );
  1162 |     }
  1163 |   }
  1164 | 
  1165 |   /**
  1166 |    * Verifies text content of an element using a case-insensitive comparison.
  1167 |    * Prefer this when the rendered value may be auto-transformed (e.g. Title
  1168 |    * Case on an Order Details popup) but the business intent is case-agnostic.
  1169 |    * @param locator - Playwright Locator of the element to read text from.
  1170 |    * @param expected - Expected text value (compared after .toLowerCase/trim).
  1171 |    * @param fieldName - Business-friendly field name for logs and error output.
  1172 |    * @param timeoutMs - Optional timeout in milliseconds (default 10000).
  1173 |    */
  1174 |   async verifyTextIgnoreCase(
  1175 |     locator: Locator,
  1176 |     expected: string,
  1177 |     fieldName: string,
  1178 |     timeoutMs: number = 10000,
  1179 |   ): Promise<void> {
  1180 |     try {
  1181 |       await expect
  1182 |         .poll(async () => ((await locator.innerText()) || "").trim().toLowerCase(), {
  1183 |           timeout: timeoutMs,
  1184 |           message: `Expected text for '${fieldName}' to equal (ignore-case) '${expected}'`,
  1185 |         })
  1186 |         .toBe(expected.trim().toLowerCase());
  1187 | 
  1188 |       console.log(
  1189 |         `✅ Verified '${fieldName}' matches (ignore-case) '${expected}'`,
  1190 |       );
  1191 |     } catch (error) {
  1192 |       const actual =
  1193 |         (await locator.innerText().catch(() => "")).trim() || "EMPTY";
  1194 |       throw new Error(
  1195 |         `❌ TEXT VERIFICATION FAILED (ignore-case)\n` +
  1196 |           `Field Name : ${fieldName}\n` +
  1197 |           `Expected   : "${expected}"\n` +
  1198 |           `Actual     : "${actual}"\n` +
  1199 |           `Reason     : ${
  1200 |             error instanceof Error ? error.message : String(error)
  1201 |           }`,
  1202 |       );
  1203 |     }
  1204 |   }
  1205 | 
  1206 |   async verifyLabelText(
  1207 |     locator: Locator,
  1208 |     expected: string,
  1209 |     fieldName: string,
  1210 |     options: {
  1211 |       exact?: boolean;
  1212 |       timeout?: number;
  1213 |       normalize?: boolean;
  1214 |     } = {},
  1215 |   ) {
  1216 |     const { exact = true, timeout = 10000, normalize = false } = options;
  1217 | 
  1218 |     try {
  1219 |       await locator.waitFor({ state: "visible", timeout });
  1220 | 
  1221 |       let actual = (await locator.innerText()) || "";
  1222 | 
  1223 |       if (exact) {
  1224 |         expect(actual.trim()).toBe(expected.trim());
  1225 |       } else {
  1226 |         expect(actual).toContain(expected);
  1227 |       }
  1228 |     } catch (error: any) {
  1229 |       const actual = (await locator.innerText().catch(() => "")) || "";
  1230 | 
  1231 |       throw new Error(
  1232 |         `❌ TEXT VERIFICATION FAILED\n` +
  1233 |           `Field Name : ${fieldName}\n` +
  1234 |           `Expected   : "${expected}"\n` +
  1235 |           `Actual     : "${actual.trim() || "EMPTY"}"\n` +
  1236 |           `Reason     : ${error.message}`,
  1237 |       );
  1238 |     }
  1239 |   }
  1240 | 
  1241 |   /**
  1242 |    * Verifies that the expected text appears in ANY of the inner texts of the
  1243 |    * elements matching the given locator. Use this when the same selector can
  1244 |    * match more than one paragraph/cell on the page (e.g. multi-record
  1245 |    * dispatch history) and the expected value lives on one of them — but not
  1246 |    * necessarily the first in DOM order.
  1247 |    *
  1248 |    * Why this exists: a plain visibility wait on a multi-match locator can
```