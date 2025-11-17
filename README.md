# MaxInfo: A-Training-Free-Key-Frame-Selection-Method-Using-Maximum-Volume-for-Enhanced-Video-Understanding

Modern Video Large Language Models (VLLMs) often rely on uniform frame sampling for video understanding, but this approach frequently fails to capture critical information due to frame redundancy and variations in video content. We propose MaxInfo, the first training-free method based on the maximum volume principle, which is available in Fast and Slow versions and a Chunk-based version that selects and retains the most representative frames from a video. By maximizing the geometric volume formed by selected embeddings, MaxInfo ensures that the chosen frames cover the most informative regions of the embedding space, effectively reducing redundancy while preserving diversity. This method enhances the quality of input representations and improves long video comprehension performance across benchmarks. For instance, MaxInfo achieves a 3.28% improvement on LongVideoBench and a 6.40% improvement on EgoSchema for LLaVA-Video-7B. Moreover, MaxInfo boosts LongVideoBench performance by 3.47% on LLaVA-Video-72B and 3.44% on MiniCPM4.5. The approach is simple to implement and works with existing VLLMs without the need for additional training and very lower latency, making it a practical and effective alternative to traditional uniform sampling methods.

# Citation
```bibtex
@article{li2025maxinfo,
  title={Maxinfo: A training-free key-frame selection method using maximum volume for enhanced video understanding},
  author={Li, Pengyi and Abdullaeva, Irina and Gambashidze, Alexander and Kuznetsov, Andrey and Oseledets, Ivan},
  journal={arXiv preprint arXiv:2502.03183},
  year={2025}
}# MaxInfo
# MaxInfo
