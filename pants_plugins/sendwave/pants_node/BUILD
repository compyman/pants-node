python_sources(
    name="pants_node_library",
    dependencies=["pants_plugins:pants", "//:sendwave-pants-docker"],
)

python_distribution(
    name="pants_node",
    dependencies=[":pants_node_library"],
    provides=setup_py(
        name="sendwave-pants-node",
        version="1.1.3",
        description="Pants Plugin to build node bundles",
        url="https://github.com/compyman/pants-node",
        author="Nathan Rosenbloom, Jean Cochrane",
        author_email="engineering@sendwave.com",
    ),
    sdist=True,
    wheel=True,
)
