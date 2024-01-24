# Neural_networks_as1

non-programming assignment 
1.	How does natural neuron work?
Soln: Natural neurons in the brain and nervous system function through electrical and chemical processes. Initially, they maintain a resting potential due to ion concentration differences across their membrane, primarily involving sodium and potassium ions. When stimulated, the neuron's membrane ion channels open, potentially leading to an action potential, an electrical signal that travels along the axon. This action potential is facilitated by ion channels and can be accelerated in myelinated axons. Upon reaching the axon terminals, the action potential triggers the release of neurotransmitters, which cross the synaptic gap and bind to receptors on the next neuron. This binding can either excite or inhibit the receiving neuron. The signal ends when neurotransmitters are broken down, reabsorbed, or diffuse away. The overall process, including the generation of post-synaptic potentials that may trigger further action potentials, enables neurons to communicate, underpinning all neural activities from reflexes to complex cognitive functions.

2.	How does natural neuron transmit signal to other neurons?
Soln: Action Potential Arrival: Signal transmission starts when an action potential, an electrical impulse, travels along the axon of the presynaptic neuron (the neuron sending the signal) until it reaches the neuron's axon terminals. The arrival of the action potential at the axon terminals triggers the opening of voltage-gated calcium channels. Calcium ions then flood into the neuron, creating a cascade of events that lead to the release of neurotransmitters. These neurotransmitters are stored in vesicles within the presynaptic neuron. The influx of calcium ions causes these vesicles to merge with the presynaptic membrane, releasing their contents (neurotransmitters) into the synaptic cleft, the small gap between the presynaptic and postsynaptic neurons. Once in the synaptic cleft, neurotransmitters diffuse across the gap and bind to specific receptors on the surface of the postsynaptic neuron. These receptors are tailored to specific neurotransmitters, ensuring precise signaling. The binding of neurotransmitters to their receptors on the postsynaptic neuron leads to changes in the neuron’s membrane potential. This can result in excitatory or inhibitory post-synaptic potentials. Excitatory neurotransmitters increase the likelihood of the postsynaptic neuron firing its own action potential, while inhibitory neurotransmitters decrease this likelihood. If the cumulative effect of all excitatory and inhibitory signals reaching the postsynaptic neuron crosses a certain threshold, it generates its own action potential, thus propagating the neural signal. If the threshold is not met, the postsynaptic neuron remains inactive. The effect of the neurotransmitter is terminated in several ways: reuptake by the presynaptic neuron, enzymatic breakdown within the synaptic cleft, or diffusion away from the synapse. This termination is crucial to prevent continuous stimulation of the postsynaptic neuron and to ready the synapse for the next signal.

3.	Describe the McCulloch and Pitts model of artificial neuron?
Soln: 
Binary Output: The model proposed that each neuron can be simplified to a binary output unit, meaning it either fires or does not fire. This firing is analogous to an action potential in biological neurons.
Inputs and Weights: The neuron receives multiple inputs, which in the original model were either on (1) or off (0), similar to binary signals. Although the original model did not include variable weights for these inputs, in later adaptations, weights were introduced to represent the strength or importance of each input.
Summation and Threshold: The inputs are summed together, and if the total exceeds a certain threshold, the neuron 'fires' and outputs a signal (often represented as 1). If the summed input does not reach the threshold, the neuron does not fire (output is 0). This is akin to the all-or-nothing principle of action potentials in biological neurons.
Activation Function: The decision of whether the neuron fires is determined by an activation function, which in the case of McCulloch and Pitts was a simple step function based on the threshold.
Logic Gates Representation: One of the key insights of the McCulloch and Pitts neuron was that it could be used to model logical operations like AND, OR, and NOT gates. By appropriately setting the thresholds and the input weights, the neuron could replicate these fundamental logic operations.
Networks of Neurons: While a single McCulloch-Pitts neuron could perform simple logical operations, networks of such neurons could be combined to perform more complex computations. This concept is a precursor to modern neural networks in artificial intelligence.
Limitations and Advancements: The original model was limited in that it did not account for learning (the adjustment of weights based on experience), which is a crucial aspect of modern neural networks. Later models introduced concepts like learning rules and backpropagation to address these limitations.
Overall, the McCulloch and Pitts model was a pioneering step in the field of computational neuroscience and artificial intelligence, providing a simplified abstraction of how neurons in the brain work and interact to process information.