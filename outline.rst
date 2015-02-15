10 Simple Rules for Releasing Your Open Source Software

1. **Test it!** That your code produces the desired output(s) from one
   set of inputs in one particular location does not mean it is ready
   for general use. Try to setup and run your code on another, fresh
   platform; better yet, give your code and docs to a friend on
   another system and see it s/he can reproduce your results.

2. Determine your audience: who might want to use your software? Are
   your requirements like theirs? If your current implementation is
   too narrowly targeted, perhaps you should generalize a bit before
   you release your current code. Alternatively, if your code does too
   many unrelated tasks, consider breaking it up into smaller parts:
   they might be easier to test and to pipeline.

3. Choose a license for your software.

4. Put it on a hosting site

   (OR, make it available via version control site)

5. Provide example input data, example results, and instructions on
   how to use your software to go from the data to the results.

6. Provide (minimal) installation and execution instructions. If you
   *can* provide more documentation, point to it from your minimal
   instructions.

7. Provide citation information.

8. For each release, provide a tag or a version number in your source
   code repository.

9. Give an estimate of the compute requirements for running your software.

10. Describe the input and output formats, as formally as you can.
