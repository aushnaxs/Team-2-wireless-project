## Literature Review: The Sustainability Paradox in AI-Driven Green Wireless Networks

Artificial intelligence (AI) is playing an increasingly important role in the evolution of wireless communication systems, particularly with the development of 6G networks. As these systems become more complex, AI is expected to improve network performance by enabling faster, more adaptive, and data-driven decision-making. This has led many researchers to view AI as a key tool for improving efficiency and reducing energy consumption. However, alongside these benefits, there is growing concern that the computational demands required to train and operate AI systems may offset these gains. This tension forms what is commonly described as the sustainability paradox: AI simultaneously enhances and challenges environmental sustainability in wireless networks. As a result, evaluating the true impact of AI requires moving beyond isolated efficiency gains and considering system-level trade-offs.

## AI as a Tool for Green and Efficient Networks

A substantial body of literature positions AI as a major driver of energy efficiency in wireless communication systems. For example, Mao et al. (2022) demonstrate that machine learning techniques can optimize power control, resource allocation, and network operations, thereby reducing unnecessary energy consumption. Similarly, Cui et al. (2025) argue that AI will become a foundational component of 6G network architecture, enabling predictive traffic management and energy-aware decision-making. Collectively, these studies suggest that AI-driven adaptability allows networks to respond dynamically to demand, minimizing resource over-provisioning and improving efficiency.

This perspective is further supported by decentralized approaches. Fernando et al. (2024) show that edge-based AI in Industrial Internet of Things (IIoT) systems can reduce communication energy costs by processing data locally. Likewise, Yousefpour et al. (2023) propose Green Federated Learning, where model training is distributed across devices to reduce communication overhead. While these approaches reduce transmission-related energy consumption, they primarily focus on localized improvements within the network layer. As a result, they often overlook the cumulative computational burden introduced by continuous and distributed AI operations. This suggests that current studies may overstate the sustainability benefits of AI by emphasizing localized efficiency gains without fully accounting for system-wide energy consumption. This also reflects a broader rebound effect, where improvements in efficiency can drive increased usage, ultimately offsetting potential environmental benefits.

## The Environmental Cost of AI Systems

In contrast, another body of research highlights the significant environmental cost associated with AI systems. Strubell et al. (2020) show that training large deep learning models such as BERT and GPT-2 requires substantial computational resources, resulting in high electricity consumption and increased carbon emissions. Their work further emphasizes that repeated experimentation and model tuning can significantly amplify these costs, even when performance improvements are marginal.

Although advances in hardware have improved the efficiency of individual models, the overall environmental impact of AI continues to increase due to the rapid growth in model size, frequency of retraining, and large-scale deployment. This indicates that improvements at the model level may be offset by expansion at the system level. In addition, factors such as data center efficiency, cooling requirements, and energy sources introduce further variability in environmental impact. Consequently, AI sustainability cannot be evaluated solely at the model level but must account for the broader computational ecosystem.

## The Sustainability Paradox in Current Research

Taken together, the literature reveals a significant but unresolved paradox: while AI improves efficiency at the network layer, it may simultaneously increase energy demands in the computational systems that underpin it. This issue is especially important in the context of 6G systems, where AI is expected to operate continuously across edge devices, base stations, and cloud environments.

As noted by Safitra et al. (2023), sustainable networking must account for the full lifecycle of digital infrastructure, including hardware production, cooling systems, and long-term operational costs. However, many studies focus on isolated system layers, leading to fragmented assessments of sustainability. As a result, current research may overestimate the environmental benefits of AI-driven optimization by overlooking its broader systemic impact. This highlights the need for more holistic evaluation frameworks that integrate both network-level efficiency and the environmental cost of AI systems.

## Research Gap and Future Direction

Despite extensive research on both AI-enabled optimization and AI-related energy consumption, relatively few studies examine these factors within a unified framework. Most existing work focuses on either performance improvements or computational costs in isolation, making it difficult to assess the overall environmental impact of AI in wireless systems.

This points to a clear research gap: the lack of evaluation frameworks that can determine whether the energy savings from AI actually outweigh the costs of training, deployment, and maintenance in real-world conditions. Possible directions include lightweight models, adaptive inference strategies, and energy-aware system design. However, it is still unclear how effective these approaches are, mainly due to limited large-scale empirical validation.

## The Hidden Energy Cost of AI Computation

While AI systems promise to improve communication efficiency, several recent studies highlight a significant but often overlooked cost: high energy consumption. One of the most widely cited studies, conducted by Emma Strubell, demonstrates that large deep learning models require substantial computational resources, often involving multiple training cycles on GPUs, leading to increased power usage. 

This issue is particularly pronounced in wireless communication systems, where AI models must be updated frequently due to the dynamic nature of communication channels. Factors such as user mobility, interference, and fluctuating demand require continuous adaptation, preventing models from remaining static.

According to Ezzeddine et al., many studies on energy efficiency in communication systems overlook the power consumption associated with inference engines, orchestration systems, and centralized AI controllers. Their analysis shows that while some AI-based solutions reduce energy consumption at the radio layer, these gains are often offset by increased power demands at other levels, including edge servers and cloud accelerators.


## Data Centers, AI Hardware, and Carbon Impact

Another factor that is often overlooked is that the sustainability of AI depends heavily on the hardware it runs on. Modern AI systems rely on high-performance processors, specialized accelerators, memory systems, and cooling technologies, all of which contribute to overall energy consumption.

As wireless networks continue to adopt AI-driven solutions, they become increasingly dependent on distributed computing nodes that essentially function as data centers. This shift has important environmental implications, as energy use extends beyond wireless transmission to include the operation and maintenance of supporting hardware.

According to Kamran et al., future 6G networks are expected to include intelligent orchestration layers capable of continuous learning. Without the use of lightweight and energy-efficient AI models, this could lead to a significant increase in overall infrastructure power consumption.


## Contradictions in Current Research

A key contradiction in current research is that many studies report significant energy savings at the local level, while few evaluate whether these savings translate into system-wide reductions. For example, a 15% decrease in network power consumption achieved through an AI model may still require continuous inference on edge devices, potentially increasing overall energy use. This suggests that improvements in communication efficiency alone do not provide a complete picture of sustainability.

A second contradiction relates to model scale. While smaller AI models often demonstrate clear energy savings, larger models deployed across thousands of network devices can result in substantial energy demand. This indicates that sustainability is strongly influenced by factors such as model size, computational complexity, and retraining frequency.

## Future Research Direction
The direction of future research on green wireless communication systems includes lightweight AI models, sparse neural networks, adaptive inference, and energy-aware model selection.

The low-power edge accelerators and model activation strategies could enable wireless communication systems to utilize AI only when performance benefits justify power consumption.

Federated learning also presents an area for improvement, where communication rounds can be costly if not managed.

## Summary
The above literature review confirms that, indeed, AI has a dual impact on green wireless communication systems. While AI provides an efficient solution to address some of the inefficiencies in wireless communication systems, improve spectrum efficiency, and enable autonomous resource management, it also has a significant impact on computational power consumption, thereby limiting some of the benefits of AI. The sustainability paradox, therefore, remains an important area of concern for future wireless communication systems, particularly with 6G's autonomous design.
