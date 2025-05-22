# 机械臂抓取方法研究
# 单机械臂（条件扩散模型）  
# 去噪条件的改变  
论文：Diffusion Policy: Visuomotor Policy Learning via Action Diffusion（RSS2023)  
链接：https://arxiv.org/abs/2303.04137  
说明：去噪条件为图像+动作  
论文：DexDiffuser: Generating Dexterous Grasps with Diffusion Models  
链接：https://arxiv.org/abs/2402.02989  
说明：去噪条件为3D点云  
论文：3D Diffusion Policy: Generalizable Visuomotor Policy Learning via Simple 3D Representations（RSS2024）  
链接：https://arxiv.org/abs/2403.03954  
说明：去噪条件为3D点云+动作信息  
论文：3D Diffuser Actor: Policy Diffusion with 3D Scene Representations  
链接：https://arxiv.org/abs/2402.10885  
说明：去噪条件为3D点云+动作信息+语言，但与3D DP不同的是，其3D点云是通过图像加深度图unprojection得到的   
论文：Learning Universal Policies via Text-Guided Video Generation  
链接：https://arxiv.org/abs/2302.00111  
说明：输入文本和图像扩散生成抓取视频，再通过逆动力学模型将图像转为动作  
论文：Language-Guided Object-Centric Diffusion Policy for Generalizable and Collision-Aware Robotic Manipulation（ICRA2025）  
链接：https://arxiv.org/abs/2407.00451  
说明：利用大模型将物体分为障碍物和目标，输入3D点云+动作信息扩散成轨迹  
论文：Hierarchical Diffusion Policy for Kinematics-Aware Multi-Task Robotic Manipulation（CVPR2024）  
链接：https://arxiv.org/html/2403.03890v1  
# 分层架构  
说明：分层扩散模型，高层预测关键帧，低层进行扩散生成  
论文：AdaptDiffuser: Diffusion Models as Adaptive Self-evolving Planners（ICML2023 Oral)  
链接：https://arxiv.org/abs/2302.01877  
# 自适应  
论文：AdaptDiffuser: Diffusion Models as Adaptive Self-evolving Planners  
链接：https://arxiv.org/abs/2302.01877  
说明：AIGC赋能扩散模型，同一模型可以适应不同任务  
# 多机械臂（扩散模型）  
论文：RoboFactory: Exploring Embodied Agent Collaboration  with Compositional Constraints  
链接：https://export.arxiv.org/abs/2503.16408  
# 单机械臂（VLA）
论文：OpenVLA: An Open-Source Vision-Language-Action Model  
链接：https://arxiv.org/abs/2406.09246  
论文：TinyVLA: Towards Fast, Data-Efficient Vision-Language-Action Models for Robotic Manipulation  
链接：https://arxiv.org/abs/2409.12514  
说明：VLA+扩散模型  
论文：RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control（谷歌）  
链接：https://arxiv.org/abs/2307.15818  
论文：DexGraspVLA: A Vision-Language-Action Framework Towards General Dexterous Grasping  
链接：https://arxiv.org/abs/2502.20900  
说明：分层框架，以VLM作为高层，以扩散模型作为底层  
# 多机械臂（VLA） 
论文：π0: A Vision-Language-Action Flow Model for  General Robot Control（物理智能）  
链接：https://arxiv.org/abs/2410.24164  
论文：π0.5: a Vision-Language-Action Model with  Open-World Generalization（物理智能）  
链接：https://arxiv.org/html/2504.16054v1  
