# RPiDog
RPiDog使用情景模拟器生成的情景数据作为微调数据集，使用Xtuner工具基于llava-v1.6-vicuna-7b
模型进行微调，然后使用LlamaEdge运行模型推理，部署到机器狗板载Raspberry Pi上离线部署。
它能实现以下三方面功能
思考功能：人机自然语言交互、复杂任务规划等；感知功能：对场景进行视觉感知；运动功能：接受传感器数据、控制电机等硬件。
