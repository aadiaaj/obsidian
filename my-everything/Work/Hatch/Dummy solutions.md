`const { isSolutionsLoading } = useSolutionsContext();`

`const allSolutions = [`

`{`

`id: "sol-001",`

`name: "AI Customer Segmentation",`

`description:`

	``"Machine learning solution for automated customer segmentation based on behavior patterns",``

`createdAt: new Date("2025-01-15"),`

`updatedAt: new Date("2025-04-22"),`

`categoryId: "cat-001",`

`category: {`

	``id: "cat-001",``

	``name: "Marketing",``

	``description: "Marketing solutions",``

`},`

`solutionTypeId: "sol-type-001",`

`solutionType: { id: "sol-type-001", name: "Analytics" },`

`rating: 4.7,`

`popularity: 325,`

`status: "Published",`

`isPublished: true,`

`creator: {`

	``id: "usr-001",``

	``name: "Alex Johnson",``

	``email: "alex.j@example.com",``

	``role: "admin",``

`},`

`tags: ["ai", "segmentation", "marketing"],`

`viewCount: 1250,`

`isSaved: false,`

`isFavorite: true,`

`customInstructions: "Use with customer data in CSV format.",`

`knowledgeSources: [],`

`conversationStarters: [`

	``"How can I segment my customer base?",``

	``"What patterns exist in my customer data?",``

`],`

`widgetsConfig: {},`

`},`

`{`

`id: "sol-002",`

`name: "Document Extraction API",`

`description:`

	``"API for extracting structured data from unstructured documents",``

`createdAt: new Date("2025-02-20"),`

`updatedAt: new Date("2025-04-10"),`

`categoryId: "cat-002",`

`category: {`

	``id: "cat-002",``

	``name: "Document Processing",``

	``description: "Document handling solutions",``

`},`

`solutionTypeId: "sol-type-002",`

`solutionType: { id: "sol-type-002", name: "API" },`

`rating: 4.2,`

`popularity: 210,`

`status: "Published",`

`isPublished: true,`

`creator: {`

	``id: "usr-002",``

	``name: "Taylor Smith",``

	``email: "taylor.s@example.com",``

	``role: "user",``

`},`

`tags: ["document", "extraction", "api"],`

`viewCount: 780,`

`isSaved: true,`

`isFavorite: false,`

`customInstructions: "Supports PDF, DOCX, and image formats.",`

`knowledgeSources: [],`

`conversationStarters: [`

	``"How do I extract text from PDFs?",``

	``"Can I convert scanned documents to structured data?",``

`],`

`widgetsConfig: {},`

`},`

`{`

`id: "sol-003",`

`name: "Predictive Maintenance Dashboard",`

`description: "Real-time equipment monitoring with failure prediction",`

`createdAt: new Date("2025-03-05"),`

`updatedAt: new Date("2025-05-01"),`

`categoryId: "cat-003",`

`category: {`

	``id: "cat-003",``

	``name: "Manufacturing",``

	``description: "Manufacturing optimization solutions",``

`},`

`solutionTypeId: "sol-type-003",`

`solutionType: { id: "sol-type-003", name: "Dashboard" },`

`rating: 4.9,`

`popularity: 450,`

`status: "Published",`

`isPublished: true,`

`creator: {`

	``id: "usr-003",``

	``name: "Jordan Rivera",``

	``email: "jordan.r@example.com",``

	``role: "admin",``

`},`

`tags: ["predictive", "maintenance", "manufacturing", "iot"],`

`viewCount: 1620,`

`isSaved: true,`

`isFavorite: true,`

`customInstructions: "Connect to IoT sensors via REST API or MQTT.",`

`knowledgeSources: [],`

`conversationStarters: [`

	``"How can I predict equipment failures?",``

	``"What metrics should I monitor for preventative maintenance?",``

`],`

`widgetsConfig: {`

	``charts: {``

		``enabled: true,``

		``types: ["line", "gauge"],``

	``},``

`},`

`},`

`];`