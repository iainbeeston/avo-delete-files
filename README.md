# README

This rails app demonstrates a bug in avo's file field, where
it's possible to upload an attachment but deleting it causes
a 404 error.

Instructions:

1. `bin/rails s`
2. Go to https://localhost:3000/avo
3. Create a person with a photo file
4. Delete the photo file

This causes the error
