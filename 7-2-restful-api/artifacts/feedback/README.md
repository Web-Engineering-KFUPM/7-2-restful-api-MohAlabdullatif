# 7-2-RESTFul-APIs-main — Feedback

## Submission

- **Lab:** 7-2-RESTFul-APIs-main
- **Deadline (Riyadh / UTC+03:00):** 2026-04-15T20:59:00+03:00
- **Last commit time (from git log):** 2026-04-15T06:52:55.827Z
- **Submission marks:** **20/20** (On time)


## Files Checked

- Repo root (cwd): C:\Users\kelve\Desktop\MyStuff\KFUPM\252\SWE363\Participation\7.2\7-2-restful-api-MohAlabdullatif\7-2-restful-api
- Detected project root: C:\Users\kelve\Desktop\MyStuff\KFUPM\252\SWE363\Participation\7.2\7-2-restful-api-MohAlabdullatif\7-2-restful-api
- Server directory: ✅ C:\Users\kelve\Desktop\MyStuff\KFUPM\252\SWE363\Participation\7.2\7-2-restful-api-MohAlabdullatif\7-2-restful-api\server
- server.js: ✅ C:\Users\kelve\Desktop\MyStuff\KFUPM\252\SWE363\Participation\7.2\7-2-restful-api-MohAlabdullatif\7-2-restful-api\server\server.js
- song.model.js: ✅ C:\Users\kelve\Desktop\MyStuff\KFUPM\252\SWE363\Participation\7.2\7-2-restful-api-MohAlabdullatif\7-2-restful-api\server\models\song.model.js

---

## TODO-by-TODO Feedback

### TODO 2: Import dotenv and load environment — **10/10**

**Checklist**
- ✅ Imports dotenv using import dotenv from "dotenv"
- ✅ Calls dotenv.config()

**Deductions / Notes**
- ✅ No deductions. Good job!

### TASK 2: Create Song schema and model — **18/18**

**Checklist**
- ✅ Imports mongoose in song.model.js
- ✅ Defines a schema using new mongoose.Schema(...)
- ✅ Schema includes title field
- ✅ Schema includes artist field
- ✅ Schema includes year field
- ✅ title field uses String type
- ✅ artist field uses String type
- ✅ year field uses Number type
- ✅ Creates model named "Song"
- ✅ Exports Song model

**Deductions / Notes**
- ✅ No deductions. Good job!

### TODO 3: POST /api/songs — **18/18**

**Checklist**
- ✅ Defines POST route for "/api/songs"
- ✅ Uses Song.create(...) or new Song(...).save()
- ✅ Reads req.body
- ✅ Uses title from request body
- ✅ Uses artist from request body
- ✅ Responds with status 201 on success
- ✅ Handles error with status 400

**Deductions / Notes**
- ✅ No deductions. Good job!

### TODO 4: GET /api/songs and GET /api/songs/:id — **12/12**

**Checklist**
- ✅ Defines GET route for "/api/songs"
- ✅ Uses Song.find()
- ✅ Sorts by createdAt descending or newest first
- ✅ Defines GET route for "/api/songs/:id"
- ✅ Uses Song.findById(...)
- ✅ Returns 404 when song is not found

**Deductions / Notes**
- ✅ No deductions. Good job!

### TODO 5: PUT /api/songs/:id — **11/11**

**Checklist**
- ✅ Defines PUT route for "/api/songs/:id"
- ✅ Uses Song.findByIdAndUpdate(...)
- ✅ Uses req.params.id
- ✅ Uses req.body for update data
- ✅ Uses new: true
- ✅ Uses runValidators: true
- ✅ Returns 404 when song is not found

**Deductions / Notes**
- ✅ No deductions. Good job!

### TODO 6: DELETE /api/songs/:id — **11/11**

**Checklist**
- ✅ Defines DELETE route for "/api/songs/:id"
- ✅ Uses Song.findByIdAndDelete(...)
- ✅ Uses req.params.id
- ✅ Returns 404 when song is not found
- ✅ Returns 204 on successful delete

**Deductions / Notes**
- ✅ No deductions. Good job!

---

## How marks were deducted (rules)

- JS comments are ignored, so starter TODO comments do NOT count.
- The grader checks `server.js` and `server/models/song.model.js`.
- `.env` is intentionally excluded from grading.
- `db.js` is intentionally excluded from grading.
- Checks are intentionally lenient and verify top-level implementation only.
- Code can be in ANY order; repeated code is allowed.
- Common equivalents are accepted where possible.
- npm install commands and manual testing commands are NOT graded.
- Missing required items reduce marks proportionally within that TODO.
- The script checks for the required REST API structure, not exact wording.
