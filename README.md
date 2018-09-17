# Simple and effective text clustering

### Input: list of documents:
 - HLV Park Hang Seo nói gì sau chiến thắng tưng bừng trước Pakistan?
 - HLV Park Hang-seo 'mất niềm tin', tiết lộ về 2 pha hỏng ăn penalty liên tiếp của Công Phượng
 - Xả súng kinh hoàng tại Điện Biên khiến 2 vợ chồng tử vong
 - Nghi án nổ súng ở Điện Biên, hai vợ chồng tử vong tại chỗ
 - Sập cầu ở Ý, 35 người thiệt mạng
 - Công Phượng đá hỏng 2 quả penalty, bố mẹ ở nhà nghĩ gì?
     
     
### Output: list of clusters:
 - Cluster 1:
     - HLV Park Hang Seo nói gì sau chiến thắng tưng bừng trước Pakistan?
     - HLV Park Hang-seo 'mất niềm tin', tiết lộ về 2 pha hỏng ăn penalty liên tiếp của Công Phượng
 - Cluster 2:
      - Xả súng kinh hoàng tại Điện Biên khiến 2 vợ chồng tử vong
      - Nghi án nổ súng ở Điện Biên, hai vợ chồng tử vong tại chỗ
 - Noises:
      - Sập cầu ở Ý, 35 người thiệt mạng
 
### Approach: connected components Clustering

<img src="Example.png">


