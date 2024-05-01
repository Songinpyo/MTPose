# Motion-aware-heatmap-regression
Official repository of Motion-Aware Heatmap Regression for Human Pose Estimation in Videos (IJCAI2024)


## Abstract
We present an approach to solving 2D human pose estimation in videos.
The problem of human pose estimation in videos differs from estimating human poses in static images since videos contain a lot of motion related information. Thus, we investigate how to utilize by the information of the human body movements across in a sequence of video frames for estimating human poses in videos.
To do this, we introduce a novel heatmap regression method what we call motion-aware heatmap regression.
Our approach computes motion vectors in joint keypoints from adjacent frames.
We then design a new style of heatmap that we call \textbf{\textit{Motion-Aware Heatmaps}} to reflect the motion uncertainty of each joint point.
Unlike traditional heatmaps, our motion-aware heatmaps not only consider the current joint locations but also account how joints move over time.
Furthermore, we introduce a simple yet effective framework designed to incorporate motion information into heatmap regression.
We evaluate our motion-aware heatmap regression on PoseTrack(2018, 21) and Sub-JHMDB datasets.
Our results validate that the proposed motion-aware heatmaps significantly improve the precision of human pose estimation in videos,
particularly in challenging scenarios such as videos like sports game footage with substantial human motions.

## News
- (Soon) Codes are available.
- (2024.05) Our paper is accepted by IJCAI 2024!
