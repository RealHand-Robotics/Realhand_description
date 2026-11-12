A6 + O6 完整 URDF

解压整个文件夹，打开 robot.urdf，保留同目录 meshes。
网页查看器若要求拖入文件夹，请拖入整个 a6_o6 文件夹，而不只是 URDF。
六轴名称为 joint_1 到 joint_6，均为 revolute。
所有 mesh 路径均在当前文件夹内；不含 ../ 或 package://。
STL 字节与控制台原始模型一致，仅改写 URDF 中的文件路径。
此文件不定义实机编码器 Home，不用于自动发送硬件目标。
