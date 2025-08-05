# BAD-BVOL Benchmark

## Overview
BAD-BVOL：A novel benchmark specifically designed for 2v2 competitive sports analysis.

We have established the BAD-BVOL benchmark, a novel evaluation framework for 2v2 competitive sports analysis. This framework was constructed through systematic annotation of professional match videos and includes two professional sports datasets with significant tactical differences: beach volleyball and badminton. The beach volleyball dataset demonstrates an open tactical system that allows teams to pass the ball, while the badminton dataset presents a closed tactical system with strict restrictions on passing. The BAD-BVOL benchmark provides a unique data foundation for studying the differentiated impacts of team collaboration and individual skills in 2v2 competitive sports by comparing these two tactical systems. Specific annotation specifications include:

Frame-level action time boundaries: Precise annotation of the start and end frames for each action.
Ball possession status: Record the index of the ball-holding player, corresponding to the positions of top-left, bottom-left, top-right, or bottom-right in 2v2 sports events.
Scoring status: Record the scoring status of each sequence.

## Dataset Description

Due to GitHub's restrictions on individual file sizes (files larger than 100MB require Git LFS), only some of the annotated data files in CSV format have been uploaded to the current repository. The complete BAD-BVOL benchmark dataset includes:

- Annotation files (CSV format): Partial samples have been uploaded
- Raw videos (MP4 format): Due to the average size of individual video files exceeding 500MB, they have not yet been uploaded

**Data Acquisition Methods**:
1. Current version: The data structure can be understood through the provided CSV sample files
2. Full version: After the paper is accepted, a complete download link will be provided via [Google Drive] (including all videos and corresponding annotations)  
