# Firestore rules tests

Run locally (needs Node 18+ and Java 11+):

```
npm i -D firebase-tools@13 @firebase/rules-unit-testing@3 firebase@10
npx firebase emulators:exec --only firestore --project demo-ibf "node tests/rules.test.js"
```

Expected output ends with `PASS <n> FAIL 0`.
