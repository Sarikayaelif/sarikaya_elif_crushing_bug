# Crushing Bugs
  Troubleshooting in Drag and drop puzzles project.

## Roadmap
there are two bugs needs to solve
1. all parts in the drag zone could be dragged into the drop zone even if they were wrong, and also two puzzle pieces could be draged and drooped into same drop zone. To solve this bug, datasets are created so that puzzle pieces go to the right places.
2. No new board was formed for the other puzzles. To solve this bug, appendchild is used in swapimages function and pieces were selected and matched to their zones by using datasets.

## MIT License
Copyright 2021 Elif Sarikaya

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
