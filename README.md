# KernelTone

## 🎵 About KernelTone
**KernelTone** is an AI-powered ambient music generator that transforms real-time system performance data into dynamic, evolving soundscapes. By integrating deep learning, granular synthesis, and system monitoring, KernelTone produces an ever-changing soundtrack that reflects the activity of your machine.

## 🌟 Objectives
- **Creating Pleasant Music**: Generate non-repetitive, immersive ambient soundscapes that adapt to real-time system performance.
- **System Dashboard Integration**: Visualize system metrics alongside generated audio, offering an intuitive experience.
- **LMA (Logging, Monitoring, and Alerting) Tool Integration**: Enable compatibility with tools like **Prometheus, Grafana, Loki, ELK stack, and OpenTelemetry** to incorporate system-wide observability into sonification.
- **Customizable AI Sound Models**: Allow users to train and tweak AI-generated sounds for personalized experiences.
- **Dockerized & Portable**: Deployable via Docker for seamless use on any system.

## 🚀 Features
- **AI-Generated Ambient Music**: Uses deep learning models to create fluid, natural soundscapes based on system load, disk I/O, network activity, and memory usage.
- **Granular Synthesis & Reverb**: Generates evolving tones and spatial sound effects.
- **System Performance-Driven Dynamics**: Music intensity changes with CPU usage, memory load, and disk activity.
- **Plug-and-Play with Monitoring Tools**: Extendable to system dashboards like Grafana, Prometheus, or custom visualization tools.
- **Configurable Sound Profiles**: Users can adjust sound profiles for different environments (calm, energetic, cyberpunk, etc.).

## 📦 Installation & Usage
### 🐳 Run with Docker
```bash
docker run --rm --device /dev/snd --net=host nindevdo/kerneltone
```

### 🏗 Manual Installation
```bash
# Clone the repository
git clone https://github.com/Nindevdo/KernelTone.git
cd KernelTone

# Install dependencies
pip install -r requirements.txt

# Run the sound generator
python generate_ambient.py
```

## 🔧 Roadmap
- [ ] Integrate real-time visualization for system metrics
- [ ] Expand AI sound models for more variation
- [ ] Web-based dashboard for remote control
- [ ] MIDI/OSC output support for advanced music setups
- [ ] Integration with observability stacks (Grafana, Prometheus, ELK)

## 🛠 Contributing
Contributions are welcome! Feel free to open issues and submit pull requests.

## 📜 License
KernelTone is open-source under the **MIT License**.

