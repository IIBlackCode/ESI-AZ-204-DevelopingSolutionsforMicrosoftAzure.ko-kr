---
ms.openlocfilehash: 40d663462e7e48bf5baeb118e1da99d4ebf89c86
ms.sourcegitcommit: b3c9969e988713afd5bfcfa551d5986d914edf2e
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/23/2022
ms.locfileid: "146565023"
---
# <a name="az-204-developing-solutions-for-microsoft-azure"></a>AZ-204: Microsoft Azure 솔루션 개발

**모든 랩 지침은 2021년 10월 15일에 업데이트되었습니다.** 현재 열려 있는 모든 이슈 및 PR을 닫고 모든 사용자가 새 지침을 검토한 후 앞으로 발생하는 새로운 변경 내용을 제출하도록 권장합니다.

> **참고**: 학생들은 랩 호스팅 공급자를 통해 AllFiles가 제공되지 않을 경우 리포지토리를 동기화하도록 지시됩니다. 

- **학생들에게** 사용하기 쉬운 랩 지침 목록인 [https://aka.ms/az204labs](https://aka.ms/az204labs)에 연결하도록 지시합니다.
- **MCT이신가요?** - [MCT를 위한 GitHub 사용자 가이드](https://microsoftlearning.github.io/MCT-User-Guide/)를 살펴보세요.
- **랩 지침을 수동으로 빌드해야 하나요?** - 지침은 [MicrosoftLearning/Docker-Build](https://github.com/MicrosoftLearning/Docker-Build) 리포지토리에서 확인할 수 있습니다. 
- 문제/PR의 진행 상황을 추적하는 [프로젝트](https://github.com/MicrosoftLearning/AZ-204-DevelopingSolutionsforMicrosoftAzure/projects/1)가 추가되었습니다.

## <a name="security-issue---february-2022"></a>보안 문제 - 2022년 2월

일부 Azure 교육 랩은 학생에게 특정 사용자 이름 및 암호를 사용하도록 지시합니다. 잘못된 행위자는 가상 머신을 지속적으로 검색하고 해당 자격 증명을 사용하여 로그인하려고 합니다.
일단 로그인한 후에는 암호화 마이닝을 위해 해당 컴퓨터가 사용되며, 다른 활동에 사용할 수 있습니다.

**수정**: 학생들은 직접 선택한 암호를 사용하도록 지시됩니다. 학생들은 랩 지침의 암호를 사용하면 안 됩니다. 암호를 제거하기 위한 랩 단계가 이번 주에 업데이트됩니다. 

## <a name="what-are-we-doing"></a>Microsoft의 역할

- 이 과정을 지원하려면 과정 콘텐츠를 자주 업데이트하여, 과정에서 사용하는 Azure 서비스를 이용해 콘텐츠를 최신 상태로 유지해야 합니다.  과정 작성자와 MCT 사이의 개방된 기여를 통해 Azure 플랫폼의 변경 내용을 적용하여 콘텐츠를 최신 상태로 유지할 수 있도록, 랩 지침과 랩 파일을 GitHub에 게시합니다.

- 이를 통해 이전에 경험하지 못한 방식으로 랩에 대한 협업을 경험하기 바랍니다. Azure가 변경하고 실시간 제공 중에 이를 먼저 발견하면 랩 소스에서 바로 개선 작업을 진행합니다. 

## <a name="how-should-i-use-these-files-relative-to-the-released-moc-files"></a>릴리스된 MOC 파일과 비교하여 이러한 파일을 사용하려면 어떻게 해야 하나요?

- 강사 핸드북과 PowerPoint는 여전히 과정 콘텐츠 교육의 기본 소스입니다.

- GitHub에서 이러한 파일은 학생 핸드북과 함께 사용하도록 설계되었지만, 중앙 리포지토리 역할을 하는 GitHub에 있기 때문에 MCT와 과정 작성자는 최신 랩 파일의 소스를 공유할 수 있습니다.

- 트레이너는 강의를 할 때마다 GitHub에서 최신 Azure 서비스를 지원하기 위해 변경된 내용을 확인하고 최신 파일을 가져와서 강의에 사용하는 것이 좋습니다.

## <a name="what-about-changes-to-the-student-handbook"></a>수강생 핸드북의 변경 사항은 어떻게 되나요?

- 학생 핸드북을 분기별로 검토하고 필요하다면 일반 MOC 릴리스 채널을 통해 업데이트합니다.

## <a name="how-do-i-contribute"></a>기고하려면 어떻게 해야 하나요?

- MCT라면 누구나 GitHub 리포지토리에서 코드 또는 콘텐츠에 대한 끌어오기 요청을 제출할 수 있으며, Microsoft와 과정 작성자는 필요하다면 콘텐츠 및 랩 코드 변경 내용을 심사하고 포함합니다.

- 버그, 변경 내용, 개선 사항 및 아이디어를 제출할 수 있습니다.  우리보다 먼저 새 Azure 기능을 찾으셨나요?  새로운 데모를 제출해 주세요!

## <a name="notes"></a>참고

### <a name="classroom-materials"></a>강의 자료

MCT와 파트너는 이러한 자료에 액세스하여 학생에게 개별적으로 제공하는 것이 좋습니다.  진행 중인 수업의 일환으로 학생들에게 GitHub로 직접 이동하여 랩 단계에 액세스하게 하면, 과정에서 다른 UI에 액세스해야 하므로 학생들은 혼란을 겪게 됩니다. 별도의 랩 지침이 제공되는 이유를 학생들에게 설명하면 클라우드 기반 인터페이스와 플랫폼의 끊임없이 변하는 특성을 강조할 수 있습니다. Microsoft Learning은 GitHub의 파일 액세스를 지원하며, GitHub 사이트 탐색 지원은 이 과정을 가르치는 MCT에게만 제공됩니다.
